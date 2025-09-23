# Comprehending commands

## Listing files
To find the file contiaing flag by search thorugh ls command

### Solve
**Flag:** `pwn.college{kZCZF2uyIy35LwmOxRLbTZ1Xe4y.QX4IDO0wiNwIzNzEzW}`

entered the /challenge directory and listed all files in it using ls. Saw a random named file. Didnt get the flag on catting directly. So ran the file path without cat, because the flag was in the executable of the file.

```bash
/challenge
ls
/challenge/32000-renamed-run-18430
```

### New Learnings
Learnt to serach for the required file using ls listing command.

### References 
pwn.college
