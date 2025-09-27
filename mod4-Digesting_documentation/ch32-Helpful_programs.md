# Digesting documents

## Helpful programs
To learn the argument in the help page of  `/challenge/challenge`

### Solve
**Flag:** `pwn.college{0uASFGRMQjHctqA8ElTRtuTJk8X.QX3IDO0wiNwIzNzEzW}`

Checkout the help page of `/challenge/challenge` using -h and found that `-p`  prints the int argument for `-g` which returns the flag.

```bash
/challenge/challenge -h
/challenge/challenge -p
/challenge/challenge -g 88
pwn.college{0uASFGRMQjHctqA8ElTRtuTJk8X.QX3IDO0wiNwIzNzEzW}
```

### New Learnings
Learnt to use -h argument to read the help file of a program.

### References 
pwn.college
