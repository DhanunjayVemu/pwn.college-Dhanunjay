# Pondering PATH

## The PATH Variable
In this level, you will disrupt the operation of the /challenge/run program. This program will DELETE the flag file using the rm command. However, if it can't find the rm command, the flag will not be deleted, and the challenge will give it to you! Thus, you must make it so that /challenge/run also can't find the rm command!

### Solve
**Flag:** `pwn.college{cwMfVFFMSsQ85XOq0Tb4hDXHgu4.QX2cDM1wiNwIzNzEzW}`

Typed ```PATH=''``` and used ```/challenge/run``` and got the flag.

```bash
PATH=''
/challenge/run
pwn.college{cwMfVFFMSsQ85XOq0Tb4hDXHgu4.QX2cDM1wiNwIzNzEzW}
```

### New Learnings
Learnt about the PATH variable.
