# Perceiving permissions

## Changing permissions
To change permission 

### Solve
**Flag:** `pwn.college{geNWE8KhqbBdGmcnxL-0p7JQYJY.QXzcjM1wiNwIzNzEzW}`

Changed the perimssion of flag file using the ```chmod``` command and gave an argument of ```o+r``` giving the other users the permission of reading the file. Hence, was able to ```cat /flag``` to get the flag.

```bash
chmod o+r /flag
cat /flag
pwn.college{geNWE8KhqbBdGmcnxL-0p7JQYJY.QXzcjM1wiNwIzNzEzW}
```

### New Learnings
Learnt to change permissions of a file.

### References 
pwn.college
