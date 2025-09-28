# Practiciing piping

## Filtering with grep -v
Filtering the data not needed using grep -v

### Solve
**Flag:** `pwn.college{Qf8wpHbZKK9QmtFJp3ozbkTm2OZ.0FOxEzNxwiNwIzNzEzW}`

Used grep -v to filter the unnecessary content in the /challende/run program (containing the word DECOY) and found the flag.

```bash
/challenge/run | grep -v DECOY
pwn.college{Qf8wpHbZKK9QmtFJp3ozbkTm2OZ.0FOxEzNxwiNwIzNzEzW}
```

### New Learnings
Learnt to use the grep -v command

### References 
pwn.college
