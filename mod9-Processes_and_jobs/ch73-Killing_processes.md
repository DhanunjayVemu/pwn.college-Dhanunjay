# Processes and jobs

## Killing processes
To kill a process

### Solve
**Flag:** `pwn.college{A8Cfs6qHomWwvILPoPYoBgo1o4e.QXyQDO0wiNwIzNzEzW}`

Grepped for the sub string 'dont_run' in ps -ef by making a pipe from ps to grep. That printed the processes which have dont_run in their commands. Found its process ID and terminated it using the kill command with its PID as the argument. Then got the flag by  running /challenge/run 

```bash
ps -ef | grep dont_run
kill 136
/challenge/run
pwn.college{A8Cfs6qHomWwvILPoPYoBgo1o4e.QXyQDO0wiNwIzNzEzW}
```

### New Learnings
Learnt to terminate a process

### References 
pwn.college
