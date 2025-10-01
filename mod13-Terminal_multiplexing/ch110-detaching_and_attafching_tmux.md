# Terminal Multiplexing

## Detaching and Attaching (tmux)
For this challenge:

Launch tmux
Detach from it.
Run /challenge/run (this will send the flag to your detached session!)
Reattach to see your prize

### Solve
**Flag:** `pwn.college{A3FCjL3FGTeX1jTe04M03q6q0yu.0VO4IDOxwiNwIzNzEzW}`

Used ```tmux``` command to launch tmux and detached from it using ```ctrl+b d``` and then attached back using ```tmux ``` and got the flag.

```bash
tmux
ctrl+b d
tmux a-
pwn.college{A3FCjL3FGTeX1jTe04M03q6q0yu.0VO4IDOxwiNwIzNzEzW}
```

### New Learnings
Learnt to detach and attach using tmux.
