# File globbing

## mixing globs
mixing different globs to match files

### Solve
**Flag:** `pwn.college{YP4fWxx9vidCE--svWbQBfFOV5F.QX1IDO0wiNwIzNzEzW}`

Tried multiple arrangements but didnt work, then realised we need three letters for which the position of each letter 
should be exclusive for each word (uniqueness to each word). So used their first letters in [] and * to the rest of the letters of other words cause * can have any letters.

```bash
/challenge/run [cep]*
pwn.college{YP4fWxx9vidCE--svWbQBfFOV5F.QX1IDO0wiNwIzNzEzW}
```

### New Learnings
Learnt to mix globs for matching required files at once.

### References 
pwn.college
