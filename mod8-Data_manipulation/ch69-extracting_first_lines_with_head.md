# Data Manipulation

## extracting first lines with head
To display first 7 lines using head and piping the output to another program. 

### Solve
**Flag:** `pwn.college{wZgYdUwuf9i_KB2gn7_o4CcEVUp.0lNxEzNxwiNwIzNzEzW}`

Made a pipe from the initial program to head command, which then is piped to /challenge/college program to store the output (7 lines display) in it. 

```bash
/challenge/run | head -n 7 | /challenge/college
```

### New Learnings
Learnt to extract lines using head.