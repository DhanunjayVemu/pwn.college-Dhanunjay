# Chaining commands

## Executing shell scripts
To Execut a shell script with bash command by giving executable permission to user. 

### Solve
**Flag:** `pwn.college{oanquLXLFTmqrSRh_5dCkF1w-5_.QX0cjM1wiNwIzNzEzW}`

First, made a shell script containing /challenge/solve. Then added executable permission to the user(root) using ```chmod```. Then ran the script shell without bash command.

```bash
echo "/challenge/solve" > script.sh
chmod u+x script.sh
./script.sh
pwn.college{oanquLXLFTmqrSRh_5dCkF1w-5_.QX0cjM1wiNwIzNzEzW}
```

### New Learnings
Learnt to run shell script without bash command.

### References 
pwn.college
