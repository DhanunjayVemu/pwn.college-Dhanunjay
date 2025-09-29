# Data Manipulation

## Translating characters
To undo the case reversal using tr

### Solve
**Flag:** `pwn.college{Q1ZMEH1rdhpQ_dn3_zwHWinB6FQ.01MxEzNxwiNwIzNzEzW}`

 firstly, used ```tr``` to swap ABC... and so on with abc... which didn't work. Since, uppercase needs to be made lowercase and vice verca ```tr a-zA-Z A-Za-z```  worked and got the right flag.

```bash
/challenge/run | tr a-zA-Z A-Za-z
```

### New Learnings
Learnt to translate characters.