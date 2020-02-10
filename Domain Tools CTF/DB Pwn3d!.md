__DB Pwn3d!__
=============

By: _Jstith_

## Challenge:

```
You just compromised a database with passwords stored as md5 unsalted hashes. Crack the hash of the 'admin' password!

42f749ade7f9e195bf475f37a44cafcb

```

## Solution:

This challenge is a great example of using hashcat. We're told that the hash is an unsalted md5, which means that it should be fairly simple to crack. To solve this, run the following command in hashcat: `hashcat -m 0 "42f749ade7f9e195bf475f37a44cafcb" /usr/share/wordlists/rockyou.txt --force`. The `-m 0` indicates an MD5, and the `/usr/share/wordlists/rockyou.txt` references the list of hashes the software is going to check against. If this confuses you, look up a tutorial on hashcat and password cracking with wordlists. The output of the program should pretty quickly show you the solution.

```
Password123
```