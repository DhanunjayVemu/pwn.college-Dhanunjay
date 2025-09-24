# Comprehending commands

## Making directories
To make a new directory and file inside that directory.

### Solve
**Flag:** `pwn.college{0pdN0Fz9vib_sq488MwZ-9xisxR.QXxMDO0wiNwIzNzEzW}`

used mkdir command and gave an argument pwn to make a directory named pwn. cd'ed to that directory and made a file named college in that directory using touch command. Ran /challenge/run to get the flag at the end.

```bash
cd /tmp
mkdir pwn
cd pwn
touch collenge
/challenge/run
pwn.college{0pdN0Fz9vib_sq488MwZ-9xisxR.QXxMDO0wiNwIzNzEzW}
```

### New Learnings
Learnt to use mkdir command to create new directories.

### References 
pwn.college
