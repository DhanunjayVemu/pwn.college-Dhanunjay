# Chaining Commands

## Scripting with Conditionals
For this challenge, write a script at /home/hacker/solve.sh that:
Takes one argument
If the argument is "pwn", output "college"
For any other input, output nothing

### Solve
**Flag:** `pwn.college{Q4YEVl8Ix8z4-bcnVFD2tB9GXeq.0lNzMDOxwiNwIzNzEzW}`

In the nano text editor, on opening the solve.sh file, i wrote the conditional statements for this challenge, as:
```bash
if [ "$1" == "pwn" ]
then 
    echo "college"
fi
``` 
Then in the normal shell, i tested it with bash command and argument as 'pwn', and it returned college. So on running ```/challenge/run``` got the flag.

```bash
bash solve.sh pwn
/challenge/run
pwn.college{Q4YEVl8Ix8z4-bcnVFD2tB9GXeq.0lNzMDOxwiNwIzNzEzW}
```


### New Learnings
Learned about scripting with conditionals.

