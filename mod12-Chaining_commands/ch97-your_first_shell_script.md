# Chaining Commands

## Your First Shell Script
To write a shell script to run two programs into a shell file.

### Solve
**Flag:** `pwn.college{knrNnqjHEnRDasyMUV03doeCmcV.QXxcDO0wiNwIzNzEzW}`

used ```echo``` with argument ```/challenge/pwn; /challenge/college``` onto ```x.sh``` and used bash on it and got the flag.

```bash
echo "/challenge/pwn; /challenge/college" > x.sh
bash x.sh
pwn.college{knrNnqjHEnRDasyMUV03doeCmcV.QXxcDO0wiNwIzNzEzW}
```

### New Learnings
Learnt about shell script.


