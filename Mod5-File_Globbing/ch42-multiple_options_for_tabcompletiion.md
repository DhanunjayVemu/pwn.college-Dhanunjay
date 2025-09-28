# File globbing

## Multiple options for tab completion
Using tab completion among multiple options to find the right file containing the flag.

### Solve
**Flag:** `pwn.college{g5CA1WyyPx9cABXTJpTa2OgSJM4.0lN0EzNxwiNwIzNzEzW}`

Cattinng the /challenge/files/p and clicking tab gave multiple options among which i chose pwnc and pressed tab again which autofilled pwncollege, then among the new options, chose(typed) -flag  and tabbed again, which on running gave the flag.

```bash
cat /challenge/files/pwn-college
cat /challenge/files/pwn-
cat /challenge/files/pwncollege-
cat /challenge/files/pwncollege-flag
pwn.college{g5CA1WyyPx9cABXTJpTa2OgSJM4.0lN0EzNxwiNwIzNzEzW}
```

### New Learnings
Learnt to find the required file among multiple options from tab completion.

### References 
pwn.college
