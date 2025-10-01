# Perceiving permissions

## permission setting practice
To overwrite permissions using =

### Solve
**Flag:** `pwn.college{0i3rOx_BtEmbrUapLFgRlGP76Q8.QXzETO0wiNwIzNzEzW}`

Changed permissions as mentioned in each round using '=' to overwrite the previous permissions,And finally changed the permission of /flag to read to get the flag using cat.

```bash
/challenge/run
chmod u=rwx,g=rx,o=- /challenge/pwn
chmod u=r,g=x,o=x /challenge/pwn
chmod u=rw,g=w,o=x /challenge/pwn
chmod u=rx,g=wx,o=wx /challenge/pwn
chmod u=r,g=rwx,o=- /challenge/pwn
chmod u=rx,g=r,o=w /challenge/pwn
chmod u=rwx,g=x,o=rwx /challenge/pwn
chmod u=wx,g=-,o=- /challenge/pwn
chmod u=r /flag
cat /flag
pwn.college{0i3rOx_BtEmbrUapLFgRlGP76Q8.QXzETO0wiNwIzNzEzW}
```

### New Learnings
Lerant to overwrite permissions. 

### References 
pwn.college
