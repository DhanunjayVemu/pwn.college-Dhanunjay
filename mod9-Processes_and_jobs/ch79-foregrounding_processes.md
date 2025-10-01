# Processes and jobs

## foregrounding processes
To run a background process in foreground

### Solve
**Flag:** `pwn.college{YMJJpQRypL_foeETI1jDhhtpHBh.QX4QDO0wiNwIzNzEzW}`

Ran a process and suspended it using ctrl-z. Then ran it in the backgorund using bg and suspended it again using ctrl-z, then using fg command and ran it in foreground.

```bash
/challenge/run
#ctrl-z
bg
fg
#enter
pwn.college{YMJJpQRypL_foeETI1jDhhtpHBh.QX4QDO0wiNwIzNzEzW}
```

### New Learnings
Learnt to run a background process in foreground.

### References 
pwn.college
