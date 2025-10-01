# Terminal Multiplexing

## Switching Windows (tmux)
We've created a tmux session with two windows:

Window 0 has the flag!
Window 1 has your warm welcome.
Go get that flag!

### Solve
**Flag:** `pwn.college{YBoP-Ly9rHPjvB3Y-eMWROgiIiW.0FM5IDOxwiNwIzNzEzW}`

Used ```tmux a``` command to attach to tmux which gave a welcome message and used ```ctrl+b 0``` to switch to window 0 and got the flag.

```bash
tmux a
ctrl+b 0
 pwn.college{YBoP-Ly9rHPjvB3Y-eMWROgiIiW.0FM5IDOxwiNwIzNzEzW}
```

### New Learnings
Learnt how to switch windows using tmux.
