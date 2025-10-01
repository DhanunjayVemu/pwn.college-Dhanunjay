# Perceiving permissions

## The SUID bit
To SUID (s instead of e) permission. 

### Solve
**Flag:** `pwn.college{EQQkx3KXn6BADMHGxx0GiwSDutJ.QXzEjN0wiNwIzNzEzW}`

Added s permission on /challenge/getroot, so anyone with the exectuable permission can run it as a root user. On setting it with s, and running /challenge/getroot, opened a root shell where the flag could be catted directly.

```bash
chmod u+s /challenge/getroot
cat /flag
ls -l /challenge/getroot
/challenge/getroot
#in the root shell: 
cat /flag
pwn.college{EQQkx3KXn6BADMHGxx0GiwSDutJ.QXzEjN0wiNwIzNzEzW}
```

### New Learnings
Brief note on what you learned from the challenge

### References 
pwn.college
