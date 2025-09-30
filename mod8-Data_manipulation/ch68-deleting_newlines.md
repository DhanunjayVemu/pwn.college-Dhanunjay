# Data Manipulation

## Deleting newlines
To delete a new lines. 

### Solve
**Flag:** `pwn.college{En3gj-PSbV3zUX3tyANu0abxuzI.0VNxEzNxwiNwIzNzEzW}`

used tr -d to delete new lines  in the /challenge/run program output and mentioned \n in double inverted quotes.

```bash
/challenge/run | tr -d "\n"
```

### New Learnings
Learnt to delete new lines.