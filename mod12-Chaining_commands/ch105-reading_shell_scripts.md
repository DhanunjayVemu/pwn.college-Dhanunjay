# Chaining Commands

## Reading Shell Scripts
In this level, we will learn to read shell scripts. /challenge/run is a shell script that requires you to put in a secret password, but that password is hardcoded into the script iself! Read the script (using, say, cat), figure out the password, and get the flag!

### Solve
**Flag:** `pwn.college{wsauevTPHVmN065FFbBCQnVF0HU.0lMwgDOxwiNwIzNzEzW}`

catted /challenge/run and got conditional code which had the password check condition in the if condition. So ran the /challenge/run program and entered that string as password to get the flag.

```bash
cat /challenge/run
/challenge/run
hack the PLANET #password
pwn.college{wsauevTPHVmN065FFbBCQnVF0HU.0lMwgDOxwiNwIzNzEzW}
```

### New Learnings
Learned about reading shell scripts.