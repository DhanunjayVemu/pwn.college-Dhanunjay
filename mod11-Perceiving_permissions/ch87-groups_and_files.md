# Perceiving permissions

## Groups and files
To change the group of a file.

### Solve
**Flag:** `pwn.college{wTi__fBGSKjkXjWVZtvURDJg2AV.QXxcjM1wiNwIzNzEzW}`

Used chgrp to change the group of the file to hacker from root. Gave hacker user and the file name /flag as the arguments to chgrp. On becoming the group memeber, was able to cat out the flag with ease.

```bash
chgrp hacker /flag
cat /flag
pwn.college{wTi__fBGSKjkXjWVZtvURDJg2AV.QXxcjM1wiNwIzNzEzW}
```

### New Learnings
Learnt to change group of a file.

### References 
pwn.college
