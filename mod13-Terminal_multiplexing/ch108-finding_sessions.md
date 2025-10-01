# Terminal Multiplexing

## Finding Sessions
In this challenge, we've created three screen sessions for you. One of them contains the flag. The other two are decoys!

### Solve
**Flag:** `pwn.college{kU6xs7CKCkKXl-JJ3N4bld-vaz1.01N4IDOxwiNwIzNzEzW}`

Used ```screen -ls``` to list out all current screens and attached each one by one until I found the right session with the flag.

```bash
screen -ls
screen -r {session}
pwn.college{kU6xs7CKCkKXl-JJ3N4bld-vaz1.01N4IDOxwiNwIzNzEzW}
```

### New Learnings
Learnt how to find sessions.
