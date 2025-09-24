# Comprehending commands

## Linking files
To run a prgoram which is symbloically linked to another program containing the flag.

### Solve
**Flag:** `pwn.college{8ah8Y8W2gaQ67wPp3tjazauwwVe.QX5ETN1wiNwIzNzEzW}`

Tried running the flag file directly but permission was denied. Since, the flag was soft linked to the path /challenge/catflag, ran that path and got the flag.

```bash
/flag
/challenge/catflag
About to read out the /home/hacker/not-the-flag file!
pwn.college{8ah8Y8W2gaQ67wPp3tjazauwwVe.QX5ETN1wiNwIzNzEzW}
```

### New Learnings
Learnt the function of soft links and its command: ln -s [old path] [new path]

### References 
pwn.college