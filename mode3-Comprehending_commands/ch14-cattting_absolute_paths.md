# Comprehending commands

## Catting absolute paths
Using cat to read the file at a given absolute path 

### Solve
**Flag:** `pwn.college{0UpSa8TOVrZPaR6b9ZITXEVRyvH.QX5ETO0wiNwIzNzEzW}`

cat command also read the file when the file's absolute path is mentioned, so wrote the absolute path of the file to run/read as a parameter to the cat command.

```bash
cat /flag
```

### New Learnings
Learnt usage of cat with absolute paths.

### References 
pwn.college
