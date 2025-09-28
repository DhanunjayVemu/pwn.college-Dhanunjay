# Practiciing piping

## Grepping errors
Grepped error using <&.

### Solve
**Flag:** `pwn.college{gQTNWeZzK77dv8VQatajV9bQLB_.QX1ATO0wiNwIzNzEzW}`

Grepped error using <&, which redirects the stderr to stdout. Then used pole operator to directly grep for flag using pwn string.

```bash
/challenge/run 2>&1 | grep pwn
pwn.college{gQTNWeZzK77dv8VQatajV9bQLB_.QX1ATO0wiNwIzNzEzW}
```

### New Learnings
Learnt to redirect file descriptor (stderr to stdout)

### References 
pwn.college
