# File globbing

## Multiple globs
To use multiple globs in same word

### Solve
**Flag:** `pwn.college{UCGl6Ld4enZL972lJ1nGKb8NeRL.0lM3kjNxwiNwIzNzEzW}`

Entered the requored directory first. Then ran the /run program with the 3 letter argument p** which didnt work, so tried *P * and that was the required glob arrangement so it gave the flag. 

```bash
cd /challenge/files
/challenge/run p**
/challenge/run *p*
pwn.college{UCGl6Ld4enZL972lJ1nGKb8NeRL.0lM3kjNxwiNwIzNzEzW}
```

### New Learnings
Learnt to use multiple globs in a single word

### References 
pwn.college