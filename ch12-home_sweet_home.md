# Pondering paths

## Home sweet home
To copy the flag from the given path to a path of a directory in the home directory

### Solve
**Flag:** `pwn.college{knDDlkL-HkPkTHQ6u-ZKS8aj8dm.QXzMDO0wiNwIzNzEzW}`

Wrote /challenge/run which had the flag as mentioned in the questions, then to copy the flag as per the given constraints, made a directory in the home directory with a single letter as the name cause it was mentioned to use only 3 letters as the path after the given path.


```bash
/challenge/run ~/b
```

### New Learnings
To make a new file in the home directory as use its path to copy the contents of another path

### References 
pwn.college
