# Pondering paths

## Position by self
To run the /challenge/run program in a specific path

### Solve
**Flag:** `pwn.college{0CjgiU9osplI9mtzx96nH6zlHqj.QX2QTN0wiNwIzNzEzW}`

first entered /challenge/run, then it showed that I'm not in the /usr/share/build-essential directory. So that is the path where I'm supposed to run the /challenge/run
program.

```bash
/challenge/run
 cd /usr/share/build-essential
/challenge/run
```

### New Learnings
Learnt to enter a specific path, i.e. change the current directory using cd and run the required program

### References 
pwn.college
