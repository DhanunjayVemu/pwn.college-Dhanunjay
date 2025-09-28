# Practiciing piping

## Grepping live output
Grepping (searching) for flag live without redirecting the output of a program.

### Solve
**Flag:** `pwn.college{4ZCc7KhdtGgimdZqb7qKeqDQA4L.QX5EDO0wiNwIzNzEzW}`

used the | (pipe operator) and grepped the flag in the /challenge/run program.

```bash
/challenge/run | grep pwn
pwn.college{4ZCc7KhdtGgimdZqb7qKeqDQA4L.QX5EDO0wiNwIzNzEzW}
```

### New Learnings
Learnt to use the pipe operator (|)

### References 
pwn.college
