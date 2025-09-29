# Practiciing piping

## Writing to multiple programs
To write output of one command as input to other commands using process substitution

### Solve
**Flag:** `pwn.college{w3-YMBU6362pL-W4nKZH5V-MSaD.QXwgDN1wiNwIzNzEzW}`

First made a pipe from /challenge/hack directly to tee of first command and made a second pipe to tee of second command. This duplicates the output of hack command and simulataneously gives it as input to /the and /planet commands.

```bash
 /challenge/hack | tee >( /challenge/the) | tee >(/challenge/planet)
pwn.college{w3-YMBU6362pL-W4nKZH5V-MSaD.QXwgDN1wiNwIzNzEzW}
```

### New Learnings
Learnt to duplicate output into commands which are process substituted.

### References 
pwn.college
