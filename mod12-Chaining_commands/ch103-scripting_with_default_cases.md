# Chaining Commands

## Scripting with Default Cases
To write a script at /home/hacker/solve.sh that:
Takes one argument
If the argument is "pwn", output "college"
For any other input, output "nope"

### Solve
**Flag:** `pwn.college{IopRdtfUeMFGU_NIGDZJOhHTVnM.01NzMDOxwiNwIzNzEzW}`

opened the nano text editor using ```nano solve.sh``` command, and wrote this conditional command in it:

```bash
if [ "$1" == "pwn" ]
then
    echo "college"
else
    echo "nope"
fi
```

```bash
bash solve.sh pwn
bash solve.sh
/challenge/run
pwn.college{IopRdtfUeMFGU_NIGDZJOhHTVnM.01NzMDOxwiNwIzNzEzW}
```

### New Learnings
Learnt about scripting with default cases.