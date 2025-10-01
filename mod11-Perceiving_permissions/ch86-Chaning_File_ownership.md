# Perceiving permissions

## Chainging file ownership
To change the file ownership using the chown command.

### Solve
**Flag:** `pwn.college{IXnK50XWpI_VIIlN0bm_x3R8yCb.QXxEjN0wiNwIzNzEzW}`

Used the chown command and gave the new user name and the file name whose ownership is to be changed. Then was able to cat out the flag. 

```bash
chown hacker /flag
cat /flag
pwn.college{IXnK50XWpI_VIIlN0bm_x3R8yCb.QXxEjN0wiNwIzNzEzW}
```

### New Learnings
Learnt to change ownership of files.

### References 
pwn.college
