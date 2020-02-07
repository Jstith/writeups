__Get XOR'd!__
==============

By: _Jstith_

## Question:

```
A string has been encrypted using single-byte XOR. Can you decrypt it and get the flag?

4b424048574b46534f424d4657
```

## Solution:

The question very helpfully tells us that there is an xor operator used somewhere in the decryption process. A good place to run XORs is good old trusty [Cyber Chef](https://gchq.github.io/CyberChef/).

Seeing that all the characters are either numbers or letters going up to F, one can guess the string is in hex. Run the string through a hex decoder on Cyber Chef, and getting an equally not useful string of plaintext. Run _that_ string through an XOR operation and you get a string of random characters, not the flag. But, there are two types of XOR operations you'll commonly see: normal and brute force. Try using the brute force XOR instead, and you'll see a ton of outputs, one of which is pretty obviously the flag.

```
HACKTHEPLANET
```