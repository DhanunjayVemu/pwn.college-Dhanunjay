# Terminal Multiplexing

## Detaching and Attaching
For this challenge, you'll need to:

Launch screen
Detach from it.
Run /challenge/run (this will secretly send the flag to your detached session!)
Reattach to see your prize

### Solve
**Flag:** `pwn.college{UbKq4Z2U80S3xLHw3ciR9ZcLSh7.0lN4IDOxwiNwIzNzEzW}`

In this challenge, I launched the screen using ```screen``` command and detached using ```ctrl+a -d``` and ran /challenge/rrun.Then attached using ```screen -r``` and got the flag.

```bash
screen
ctrl+a -d
/challenge/run
screen -r
pwn.college{UbKq4Z2U80S3xLHw3ciR9ZcLSh7.0lN4IDOxwiNwIzNzEzW}
```

### New Learnings
Learnt how to detach and attach screen.
