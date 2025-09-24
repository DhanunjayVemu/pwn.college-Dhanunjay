# comprehending commands

## hidden files
to find flag among the hidden files

### Solve
**Flag:** `pwn.college{kvq2ZjwCdf67Ob8rb-zSLhnT5OX.QXwUDO0wiNwIzNzEzW}`

used ls -a  in / (root directory) where the '-a' helped to list the hidden directories, got the flag containing directory and catted it.

```bash
cd /
ls -a
cat .flag-25385737824209
```

### New Learnings
learnt to list out hidden files whose name start with '.' using -a in ls command 

### References 
pwn.college
