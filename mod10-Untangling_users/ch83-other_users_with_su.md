# Untagling users

## Other users with su
To become another user and run a file.

### Solve
**Flag:** `pwn.college{0bzT_n6vakdW44fyctV7C29VkH8.QX2UDN1wiNwIzNzEzW}`

Became the zardus user using the su command and typing the given password. Then ran /challenge/run to get the flag.

```bash
su zardus
dont-hack-me #password
/challenge/run
pwn.college{0bzT_n6vakdW44fyctV7C29VkH8.QX2UDN1wiNwIzNzEzW}
```

### New Learnings
Learnt to become other user using the username.

### References 
pwn.college
