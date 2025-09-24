# Pondering paths

## Implicit relative path
To implicitly run a fuctiion from a directory without the /

### Solve
**Flag:** `pwn.college{wD_5sx5_eDpZI4e0BUArNpnz9Zs.QXxUTN0wiNwIzNzEzW}`

Entered the challenge directory using /challenge and had to call the run program implicitly so used, ./ because it invokes the same program.

```bash
cd /challenge
./run
```

### New Learnings
To invoke a program using implicit relative path from a directory, bypassing the bash's explicit overview of '/'

### References 
pwn.college
