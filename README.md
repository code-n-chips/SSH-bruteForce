<b>SSH-bruteForce</b>
==============
Author: Ed Fish efish001@gold.ac.uk

A simple script for connecting to a host via pxssh and brute forcing the password. For further reading consult 'Violent Python, A cookbook for hackers'. 

Bugs: Alerts user that keyboard has been grabbed. 
To do: Add cracking for SSH keys

Instructions : $>python sshBrute -H <host> -u <user> -F <password list>

Example : $>python sshBrute -H 192.168.1.100 -u root -F passwords.txt


