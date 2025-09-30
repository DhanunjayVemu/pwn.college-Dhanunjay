# Processes and Jobs

## Killing Misbehaving Processes
Killing mishaving processes (fifo)

### Solve
**Flag:** `pwn.college{0BEEtCYh7pcP7eK5ZGC_y_3nenq.0FNzMDOxwiNwIzNzEzW}`

Ran ```ps aux```, PID 142 had the decoy and killed it.Then ran ```/challenge/run``` but it got stuck at sending the flag to the fifo file. So, used cat command first on the flag_fifo file which printed many decoys. Based on the NOTE given in the instructions, interrupted the terminal and ran ```/challenge/run``` which printed:
```bash
Sending the flag to /tmp/flag_fifo!
```
Then, got the flag by using cat command on the flag_fifo file.

```bash
ps aux
kill 142
cat /tmp/flag_fifo
/challenge/run
cat /tmp/flag_fifo
pwn.college{0BEEtCYh7pcP7eK5ZGC_y_3nenq.0FNzMDOxwiNwIzNzEzW}
```

### New Learnings
Learnt to terminate misbehaving processes.