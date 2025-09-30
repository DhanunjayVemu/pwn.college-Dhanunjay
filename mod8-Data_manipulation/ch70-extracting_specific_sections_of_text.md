# Data Manipulation

## extracting specific sections of text
Extracting specific column of text and deleting the nelines.

### Solve
**Flag:** `pwn.college{06cVZIPItYmDS2sh8fiHSyNFotE.01NxEzNxwiNwIzNzEzW}`

Made a pipe from the initial prgrom to the cut command, grabbed the second column (containing flag characters) and send it through a pipe to tr -d command to delete the newlines between the characters.

```bash
 /challenge/run | cut -d " " -f 2 | tr -d "\n"
```

### New Learnings
Lerant to extract specific sections of text.