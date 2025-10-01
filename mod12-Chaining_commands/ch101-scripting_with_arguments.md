# Chaining commands

## Scripting with arguments
To make shell scripts with arguments.

### Solve
**Flag:** `pwn.college{IPi6_gC_ewLaVk8Pj11Vu_X78Iw.0VNzMDOxwiNwIzNzEzW}`

opened the script file in nano text editor using the nano command and wrote ```echo "$2 $1" ``` in it.After exiting it, ran the ```/challenge/run``` program to get the flag in the shell.

```bash
bash solve.sh pwn college
/challenge/run
pwn.college{IPi6_gC_ewLaVk8Pj11Vu_X78Iw.0VNzMDOxwiNwIzNzEzW}
```

### New Learnings
Learnt to script with arguments.

### References 
pwn.college
