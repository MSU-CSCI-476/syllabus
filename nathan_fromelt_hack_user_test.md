Nathan Fromelt
CSCI 476 Hack user test

The first step was to boot up Kali Linux which is running in VirtualBox.
Next, to learn more about the tools that were available, the tools section on kali.org was consulted.
Specifically, this page http://tools.kali.org/password-attacks/hydra.
The first attempt used a command and wordlist file found on that page, which uses 6 threads to speed up the process.

```
hydra -l test -P /usr/share/wordlists/metasploit/unix_passwords.txt -t 6 ssh://70.39.80.128
```

That attempt did not find a valid password. This is a  screen shot of the output from that try http://i.imgur.com/oWEO1CJ.png
After searching the wordlist folder, another file was found in the dirb directory (best1050.txt).
Running the same command as before with the new file, a valid password was found.
This is a screen shot of the successful attempt http://i.imgur.com/gL0Iy6t.png
After using the valid password, **changeme**, a successful login was made producing the output in the screen shot
http://i.imgur.com/MmdnZFO.png