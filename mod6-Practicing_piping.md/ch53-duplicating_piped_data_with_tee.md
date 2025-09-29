# Practiciing piping

## Duplicating piped data with tea
Duplicating piped data with tea and finding the secret argument for flag.

### Solve
**Flag:** `pwn.college{USmHX7yXa3LQ_GMKmT0AFeUQAg9.QXxITO0wiNwIzNzEzW}`

First made a pipe from /challenge/pwn to /challenge/college which on intercepting with tee in between gave a hint. The hint was to use a secret argument to /challenge/pwn which piping. Got the flag on doing that.

```bash
/challenge/pwn | tee stuff | /challenge/college
cat stuff
/challenge/pwn --secret USmHX7yX | tee smtg | /challenge/college
pwn.college{USmHX7yXa3LQ_GMKmT0AFeUQAg9.QXxITO0wiNwIzNzEzW}
```

### New Learnings
Learnt to intercept  pipelines with tee.

### References 
pwn.college
