# Processes and jobs

## processes exit codes
To checkout the exit of a process.

### Solve
**Flag:** `pwn.college{4Fq_Si6EY40ZmrMh0JBmJCyq_sJ.QX5YDO1wiNwIzNzEzW}`

echo'ed $? to checkout the exit code of /challenge/get-code and gave the exit code as an argument to /challenge/submit-code to get the flag.

```bash
/challenge/get-code
echo $?
/challenge/submit-code 128
pwn.college{4Fq_Si6EY40ZmrMh0JBmJCyq_sJ.QX5YDO1wiNwIzNzEzW}
```

### New Learnings
Brief note on what you learned from the challenge

### References 
pwn.college
