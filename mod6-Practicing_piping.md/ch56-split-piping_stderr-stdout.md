# Practiciing piping

## Split-piping stderr and stdout
Splitting stderr and stdout into different files

### Solve
**Flag:** `pwn.college{QOzWLILk4FddHzwrXaABfejHid7.QXxQDM2wiNwIzNzEzW}`

Used pipe operator to duplicate the output of the initial command into the file descriptor 2 of /challenge/the which stores the stderr in it. 

```bash
/challenge/hack | tee 2>(/challenge/the) | tee 1>(/challenge/planet)
pwn.college{QOzWLILk4FddHzwrXaABfejHid7.QXxQDM2wiNwIzNzEzW}
```

### New Learnings
Learnt to split stderr and stdout

### References 
pwn.college
