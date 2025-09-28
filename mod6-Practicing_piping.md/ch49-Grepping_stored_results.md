# Practiciing piping

## Grepping stored results
To grep for flag in redirect output file

### Solve
**Flag:** `pwn.college{sQgpTqkRI7HeKZ_Qpyk-E2YDQaV.QX4EDO0wiNwIzNzEzW}`

First redirected the output of /challenge/run to the given path and grepped for flag using 'pwn' substring and found the flag in that file.

```bash
/challenge/run > /tmp/data.txt
grep flag /tmp/data.txt
cat flag
pwn.college{sQgpTqkRI7HeKZ_Qpyk-E2YDQaV.QX4EDO0wiNwIzNzEzW}
```

### New Learnings
Learnt to search for content in a redirected flag.

### References 
pwn.college
