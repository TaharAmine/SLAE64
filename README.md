# SLAE64 assignments for SLAE64 - 1481.
This repository contains my assignments for the SecurityTube Linux Assembly Expert (64 bit) Course:
- http://www.securitytube-training.com/online-courses/x8664-assembly-and-shellcoding-on-linux/index.html

## Assignment 1 - Password-protected TCP Bind Shell
- Bind and listen on a port.
- Read a password from the client.
- If passwords match, spawn a shell.

## Assignment 2 - Password-protected TCP Reverse Shell
- Typical reverse shell, but password-protected.
- Upon connection, user inputs a password.
- If passwords match, execute the shell.

## Assignment 3 - Egghunter
- Implement an egghunter shellcode on x86_64.
- Payload should be easily configurable.

## Assignment 4 - Encoders
- Create a custom shellcode encoding scheme.

## Assignment 5 - Reverse Engineering Shellcode
- Create three x86_64 payloads with msfvenom.
- Use GDB to dissect the payloads.
- Document the process.

## Assignment 6 - Polymorphism
- Take three x86_64 payloads from Shell-Storm.org.
- Create polymorpic versions of the three to defeat pattern matching.
- May not exceed 150% of the original size of the shellcodes.
- Bonus points for shorter versions

## Assignment 7 - Crypters
- Create a shellcode crypter.
- Can use any encryption schema.
- Can use any programming language.
