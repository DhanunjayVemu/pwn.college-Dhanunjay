# Practiciing piping

## Named pipes
To make fifo (named pipe) and use it to stdin and stdout.

### Solve
**Flag:** `pwn.college{cGjQhI2-4htavOEbf9xLtKZ1C0d.01MzMDOxwiNwIzNzEzW}`

Firstly, made a fifo using mkfifo at the path /tmp/flag_fifo. Then redirected the output of /challenge/run as input to /tmp/flag_fifo. The fifo blocked the terminal looking for the read command. Opened a new termminal and ran the cat command on /tmp/flag_fifo. So the fifo got the write and read simultaneously, which ran the required process. 

```bash
#terminal-1
mkfifo /tmp/flag_fifo
/challenge/run > /tmp/flag_fifo
#temrinal-2
cat /tmp/flag_fifo
pwn.college{cGjQhI2-4htavOEbf9xLtKZ1C0d.01MzMDOxwiNwIzNzEzW}
```

### New Learnings
Learnt about fifo and the command to make fifo (mkfifo).

### References 
pwn.college
