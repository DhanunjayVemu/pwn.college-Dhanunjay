# comprehending commands

## finding files
to find the file using the find command.

### Solve
**Flag:** `pwn.college{krAKdV-zHmyrlppSK33yV1J57t6.QXyMDO0wiNwIzNzEzW}`

Used the find command to search the flag file and started to run the files which it found. First flag file was actually a directory and didnt have the required flag. Then cd'ed to the second file path for flag file which had the required flag for this challenge.

```bash
find / -name flag
cat /usr/local/lib/python3.8/dist-packages/pwnlib/flag
cat: /usr/local/lib/python3.8/dist-packages/pwnlib/flag: Is a directory
cd /usr/local/lib/python3.8/dist-packages/pwnlib/flag
ls
__init__.py  __pycache__  flag.py
cat flag.py
#wasn't the flag we needed
cd /
cat /usr/share/locale/pa/flag
pwn.college{krAKdV-zHmyrlppSK33yV1J57t6.QXyMDO0wiNwIzNzEzW}
```

### New Learnings
Learnt to use the find command to find for a file in the filesystem.

### References 
pwn.college
