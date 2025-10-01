# Perceiving permissions

## permission tweaking practice
TO perform the required permission changes.

### Solve
**Flag:** `pwn.college{YM3fa58jeQ37YxkPBdvR45HoAYd.QXwEjN0wiNwIzNzEzW}`

Did the permission changes as mentioned after each round of permission change. Finally changed the permission of the flag file to read for user using chmod and catted it to get the flag.

```bash
/challenge/run
chmod u-w /challenge/pwn
chmod g-r /challenge/pwn
chmod uo+x /challenge/pwn
chmod u-r /challenge/pwn
chmod g+x /challenge/pwn
chmod go-x /challenge/pwn
chmod uo+wx /challenge/pwn
chmod g+w /challenge/pwn
chmod u+r /flag
cat /flag
pwn.college{YM3fa58jeQ37YxkPBdvR45HoAYd.QXwEjN0wiNwIzNzEzW}
```

### New Learnings
Learnt to change multiple permissions of files. 

### References 
pwn.college
