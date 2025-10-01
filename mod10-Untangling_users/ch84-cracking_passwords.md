# Untagling users

## Cracking passwords
To crack the password from shadown leak using john.

### Solve
**Flag:** `pwn.college{k0ZzvrO6fh7z1Om1j5pyCAtWbEg.QX3UDN1wiNwIzNzEzW}`

Used john to crack the leaked password from shadow leak file. Then became the zardus using su and the passwrod from john. Ran the run file to get the flag.

```bash
john /challenge/shadow-leak
su zardus
aardvark #password
/challenge/run
pwn.college{k0ZzvrO6fh7z1Om1j5pyCAtWbEg.QX3UDN1wiNwIzNzEzW}
```

### New Learnings
Learnt to crack leaked encrypted passwords using john.

### References 
pwn.college
