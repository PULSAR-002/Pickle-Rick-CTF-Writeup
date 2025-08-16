🥒 Pickle Rick CTF Writeup
📌 Overview

This is my detailed writeup for the Pickle Rick CTF on TryHackMe.
The main objective of this challenge is to exploit a vulnerable web application, gain access to the machine, escalate privileges, and recover Rick’s three secret ingredients.

🎯 Objectives

Enumerate the target system

Exploit web vulnerabilities to gain access

Escalate privileges to root

Capture all three secret ingredients

🔎 Enumeration

Nmap Scan

Scanned the target for open ports and services

Identified running services (e.g., HTTP, SSH, etc.)

Web Enumeration

Checked the website for hidden directories

Found login/admin panels

Explored the source code for hints

💻 Exploitation

Used discovered credentials to log into the web panel

Executed commands through the vulnerable interface

Uploaded/ran commands to gain a shell on the system

🚀 Privilege Escalation

Explored the file system for interesting files

Used misconfigured permissions and scripts to escalate privileges

Gained root access

🏆 Captured Flags

Ingredient 1 – Found in the home directory

Ingredient 2 – Discovered after deeper system exploration

Ingredient 3 – Retrieved with root access

📚 Lessons Learned

Importance of thorough web enumeration

Using default credentials and hints from source code

Basics of Linux privilege escalation

How to methodically approach a CTF challenge
