# Chaining commands

## Redirecting script output
To redirect the script output into another file using pipe.

### Solve
**Flag:** `pwn.college{4KX4jLJHzZs04Fq2qYAJ2a8dq2o.QX4ETO0wiNwIzNzEzW}`

made a shell script containing outputs of the programs pwn and college. Then piped the output of script.sh to ```/challenge/solve``` and got the flag.

```bash
echo "/challenge/pwn;/challenge/college" > script.sh
bash script.sh | /challenge/solve
pwn.college{4KX4jLJHzZs04Fq2qYAJ2a8dq2o.QX4ETO0wiNwIzNzEzW}
```

### New Learnings
Learnt to redirect script output to another program.

### References 
pwn.college
