# Chaining commands

## Understanding shebangs
To use shebangs at the beginning of files to represent the interpretor. 

### Solve
**Flag:** `Flag: pwn.college{Mb5iktCgZQyFQvUivoIscnXwnN3.0VOzMDOxwiNwIzNzEzW}`

Redirected the shebang line into the solve.sh (shell script). Appended the string "hack the planet" into the same script. Then gave the executable permission to the root user. On running the ```/challenge/run``` program, got the flag. 

```bash
echo '#!/bin/bash' >  /home/hacker/solve.sh
echo 'echo "hack the planet"' >> solve.sh
chmod u+x solve.sh
/challenge/run
Flag: pwn.college{Mb5iktCgZQyFQvUivoIscnXwnN3.0VOzMDOxwiNwIzNzEzW}
```

### New Learnings
Learnt about the shebang line.

### References 
pwn.college
