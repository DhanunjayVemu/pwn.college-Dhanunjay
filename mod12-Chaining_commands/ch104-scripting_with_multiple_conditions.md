# Chaining Commands

## Scripting with Multiple Conditions
For this challenge, write a script at /home/hacker/solve.sh that:

Takes one argument
If the argument is "hack", output "the planet"
If the argument is "pwn", output "college"
If the argument is "learn", output "linux"
For any other input, output "unknown"

### Solve
**Flag:** `pwn.college{EHfeTA1is72vt7BiRxzaWztkBdv.0FOzMDOxwiNwIzNzEzW}`

In this challenge, I first appended the entire ```if then elif else fi``` conditions into ```solve.sh``` then tried running with hack, pwn, learn as arguments and other arguments which worked. So, I ran ```/challenge/run``` and got the flag.


```bash
bash solve.sh hack
bash solve.sh pwn
bash solve.sh learn
bash solve.sh
/challenge/run
pwn.college{EHfeTA1is72vt7BiRxzaWztkBdv.0FOzMDOxwiNwIzNzEzW}
```

### New Learnings
Learned about scripting with multiple conditions.