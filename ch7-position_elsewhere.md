# Pondering paths

## Position elsewhere
To run the /challenge/run program in a specific path

### Solve
**Flag:** `pwn.college{0xm-MQVi3XXPoevELa_3KYGhihK.QX3QTN0wiNwIzNzEzW}`

first entered /challenge/run, then it showed that I'm not in the /proc/131  directory. So that is the path where I'm supposed to run the /challenge/run program.

```bash
/challenge/run
 cd /proc/131 
/challenge/run
```

### New Learnings
Learnt to enter a specific path, i.e. change the current directory using cd and run the required program

### References 
pwn.college
