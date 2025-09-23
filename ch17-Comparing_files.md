# Comprehending commands

## comparing files
Using diff command to find the additional string (flag here) in a file.

### Solve
**Flag:** `pwn.college{8jqMY-_7YpCJo8yfkjDwabUKM5Q.01MwMDOxwiNwIzNzEzW}`

used diff command to find the difference between the two text files whose paths were given, so that the additional word in one of the files is printed and is the flag for this challenge. 

```bash
diff /challenge/decoys_only.txt /challenge/decoys_and_real.txt
```

### New Learnings
Learnt usage of diff to find the additional string (flag) in a big file.

### References 
pwn.college
