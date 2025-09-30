# Processes and jobs

## Listing processes
To list all the running processes.

### Solve
**Flag:** `pwn.college{gSGwNM4ZzkH6k1NOv20zCYU6RZ2.QX4MDO0wiNwIzNzEzW}`

Had to use ps aux commadn (process status) to see all the currently running processes. Found a command in one of them which ran /challenge in a specific way. So, ran that and got the flag.

```bash
ps aux
/challenge/23590-run-29265
pwn.college{gSGwNM4ZzkH6k1NOv20zCYU6RZ2.QX4MDO0wiNwIzNzEzW}
```

### New Learnings
Learnt to use ps aux and ps-ef commands

### References 
pwn.college
