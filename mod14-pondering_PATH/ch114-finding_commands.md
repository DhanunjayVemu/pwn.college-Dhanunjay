# Pondering PATH

## Finding Commands
In this challenge, we added a win command somewhere in your $PATH, but it won't give you the flag. Instead, it's in the same directory as a flag file that we made readable by you! You must find win (with the which command), and cat the flag out of that directory!

### Solve
**Flag:** `pwn.college{cDVhoRMFBqenvVrs3QD0bqghHZs.01NzEzNxwiNwIzNzEzW}`

Typed ```which win``` to get the directory and listed the files inside it and used cat command on ```cat /challenge/paths/28954/flag``` and got the flag.

```bash
which win
cat /challenge/paths/28954/flag
pwn.college{cDVhoRMFBqenvVrs3QD0bqghHZs.01NzEzNxwiNwIzNzEzW}
```

### New Learnings
Learnt about using which command.
