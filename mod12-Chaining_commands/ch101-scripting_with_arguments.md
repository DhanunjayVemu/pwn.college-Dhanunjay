# Chaining commands

## Scripting with arguments
To make shell scripts with arguments.

### Solve
**Flag:** `pwn.college{IPi6_gC_ewLaVk8Pj11Vu_X78Iw.0VNzMDOxwiNwIzNzEzW}`

redirected the echo of $2 $1 arguments into the shell script and the ran the ```/challenge/run``` program to get the flag.

```bash
echo 'echo "$2 $1"' >solve.sh
/challenge/run
pwn.college{IPi6_gC_ewLaVk8Pj11Vu_X78Iw.0VNzMDOxwiNwIzNzEzW}
```

### New Learnings
Learnt to script with arguments.

### References 
pwn.college
