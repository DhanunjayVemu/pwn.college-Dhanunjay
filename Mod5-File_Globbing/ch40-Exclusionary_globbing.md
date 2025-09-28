# file globbing

## Exclusionary globbing
To exclude files having specific letters using !.

### Solve
**Flag:** `pwn.college{gKM_G7mVl7BnPksRx8kjONDwARi.QX2IDO0wiNwIzNzEzW}`

Used ! (exclusion) in [] glob to find files which do not contain p w n in their title. Also, ended with a * so rest of the letters of the file names are considered.

```bash
/challenge/run [!pwn]*
pwn.college{gKM_G7mVl7BnPksRx8kjONDwARi.QX2IDO0wiNwIzNzEzW}
```

### New Learnings
Learnt to match files using exclusionary glob. 

### References 
pwn.college
