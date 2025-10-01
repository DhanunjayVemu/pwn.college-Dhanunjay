# Perceiving permissions

## executable files
To change execution permission of files.

### Solve
**Flag:** `pwn.college{sEZSkdrx4Uq4J7IVn4dOKIeDsiY.QXyEjN0wiNwIzNzEzW}`

Checked the permission of the ```/challenge/run``` file using ```ls -l``` command. Found out that user, group and others had only read permission. Since, I am the root user in this challenge, i changerd the permission to user ```u``` to executable using ```chmod u+x```. Then the file was excecutable by me and ran it for the flag.

```bash
ls -l /challenge/run
chmod u+x /challenge/run
/challenge/run
pwn.college{sEZSkdrx4Uq4J7IVn4dOKIeDsiY.QXyEjN0wiNwIzNzEzW}
```

### New Learnings
Learnt to change execution permission of a file.

### References 
pwn.college
