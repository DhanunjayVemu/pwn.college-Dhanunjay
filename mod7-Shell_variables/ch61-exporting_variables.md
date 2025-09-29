# Shell Variables

## Exporting Variables
 invoke /challenge/run with the PWN variable exported and set to the value COLLEGE, and the COLLEGE variable set to the value PWN but not exported.

### Solve
**Flag:** `pwn.college{sBob-9ybGXxTU90H4SdviKO_4Qq.QXyYTN0wiNwIzNzEzW}`

In this challenge, I used ```export``` and set COLLEGE to PWN and set PWN to COLLEGE without export and invoked ```/challenge/run``` and got the flag.

```bash
export PWN=COLLEGE
COLLEGE=PWN
/challenge/run
pwn.college{sBob-9ybGXxTU90H4SdviKO_4Qq.QXyYTN0wiNwIzNzEzW}
```

### New Learnings
Learnt about exporting variables.