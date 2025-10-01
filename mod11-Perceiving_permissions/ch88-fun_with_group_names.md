# Perceiving permissions

## fun with group names
To change the the group of a file. 

### Solve
**Flag:** `pwn.college{ACf1PB2V82zDjSZ6eqVkLET9Usq.QXycjM1wiNwIzNzEzW}`

Found out what grouo I(hacker) am in using the 'id' command. Then use chgrp to change the group to the group I'm(hacker user) in. Then catted /flag for the flag. 

```bash
id
chgrp grp23111 /flag
cat /flag
pwn.college{ACf1PB2V82zDjSZ6eqVkLET9Usq.QXycjM1wiNwIzNzEzW}
```

### New Learnings
Lerant to change group of a file.

### References 
pwn.college
