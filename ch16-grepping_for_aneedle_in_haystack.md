# Comprehending commands

## grepping for a needle in a haystack
Using grep to search for a string from the file whose path is mentioned.

### Solve
**Flag:** `pwn.college{oIS_B832eSTH0AeedAlvIaSLdlK.QX3EDO0wiNwIzNzEzW}`

used grep command to serach for the substring pwn.college because all flags contain this substring, and also mentioned the absolute path of the file to serach the subtsring in. It returned the entire string contianing this substring.

```bash
grep pwn.college /challenge/data.txt
```

### New Learnings
Learnt usage of grep to find a string in a big file.

### References 
pwn.college
