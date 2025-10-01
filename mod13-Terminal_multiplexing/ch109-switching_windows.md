# Terminal Multiplexing

## Switching Windows
Attach to the session with screen -r, then use one of the key combinations above to switch to Window 1. Go get that flag!

### Solve
**Flag:** ` pwn.college{Yg-rPA8fL9jL_amnT2v5FtwnjQa.0FO4IDOxwiNwIzNzEzW}`

Used ```screen -ls``` to list out all current screens and attached to the ```challenge_session``` where it gave a welcome message and told to switch to window 0, so I used ```ctrl+a 0``` to switch and got the flag.

```bash
screen -ls
screen -r challenge_session
ctrl+a 0
 pwn.college{Yg-rPA8fL9jL_amnT2v5FtwnjQa.0FO4IDOxwiNwIzNzEzW}
```

### New Learnings
Learnt how to switch windows.
