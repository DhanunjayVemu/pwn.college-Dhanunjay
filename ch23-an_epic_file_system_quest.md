# Comprehending commands

## An epic file system quest
To find the flag from the clues found using ls, cd, cat commands.

### Solve
**Flag:** `pwn.college{YbigznEKvBcjwPwZWFNiMPyyxZL.QX5IDO0wiNwIzNzEzW}`

Kept following the clues mentioned in each hint file. After finding each hint file and on reading it, had to go back to the root directory using / and cd or cat directtly to next given path. After multiple such cd's and ls -a's finally found the flag. 

```bash
cd /
ls
cd TEASER
cat TEASER
ls /opt/linux/linux-5.4/include/linux/soc/samsung
cat /opt/linux/linux-5.4/include/linux/soc/samsung/TRACE-TRAPPED
ls -a /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/STIX-Web/SansSerif/Regular
cd /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/STIX-Web/SansSerif/Regular
ls -a
cat .BRIEF
cd /
cd /opt/linux/linux-5.4/include/config/ip/multiple
ls 
cd CLUE
cat CLUE
cd /
ls /usr/share/icons/hicolor/192x192/emblems
cat /usr/share/icons/hicolor/192x192/emblems/GIST-TRAPPED
ls /usr/share/doc/sysstat/examples
cd /usr/share/doc/sysstat/examples
ls
cat INFO
cd /
cd /opt/linux/linux-5.4/include/linux/soc/qcom
ls -a
cat .DOSSIER
cd /
cd /usr/share/javascript/mathjax/localization/en
ls
cat DISPATCH
cd /
cd /usr/share/sphinx/locale/fr
ls -a
cat .SECRET
pwn.college{YbigznEKvBcjwPwZWFNiMPyyxZL.QX5IDO0wiNwIzNzEzW}
```

### New Learnings
Learnt to apply all the commands learnt (ls, ls -a, cd, cat) till now at necessary times to find the flag.

### References 
pwn.college
