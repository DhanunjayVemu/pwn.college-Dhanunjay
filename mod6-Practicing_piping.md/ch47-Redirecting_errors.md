# Practiciing piping

## Redirecting errors
Redirecting errors using file descriptor

### Solve
**Flag:** `pwn.college{AMuWNQ2aR1f-T6_FekiFyXwdEL-.QX3YTN0wiNwIzNzEzW}`

Redirected the output of the /challenge/run program to myfile and the erros to instructions file. Got the flag in myfile.

```bash
/challenge/run >myflag 2>instruct
cat myflag
pwn.college{AMuWNQ2aR1f-T6_FekiFyXwdEL-.QX3YTN0wiNwIzNzEzW}
```

### New Learnings
Learnt to redirect error.

### References 
pwn.college
