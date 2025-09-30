# Data Manipulation

## Deleting characters
To delete a character. 

### Solve
**Flag:** `pwn.college{wZ3zFeby8P82CQ7iIqjDHT8I6-3.0FNxEzNxwiNwIzNzEzW}`

used tr -d to select which characters to delete in the /challenge/run program output

```bash
/challenge/run | tr -d ^%
```

### New Learnings
Learnt to delete characters.