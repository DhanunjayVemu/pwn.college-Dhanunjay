# Practiciing piping

## Process substitution for input
To temproarily run and store output of commands. (using named pipe)

### Solve
**Flag:** `pwn.college{MAcraNWzpSw-P452Y9WSEblAoQP.0lNwMDOxwiNwIzNzEzW}`

 used diff <(command1) <(command2) -instead of comparing both commands by storing their outputs in a file and comparing the files. I've temporarily stored their outputs and found the diff which is the flag. 


```bash
diff <(/challenge/print_decoys) <(/challenge/print_decoys_and_flag)
pwn.college{MAcraNWzpSw-P452Y9WSEblAoQP.0lNwMDOxwiNwIzNzEzW}
```

### New Learnings
Learnt to use named pipe.

### References 
pwn.college
