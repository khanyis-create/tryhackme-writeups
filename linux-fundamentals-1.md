**TryHackMe — Linux Fundamentals Part 1 | Room Writeup**

This room introduced the fundamentals of using Linux, which is an essential skill for any cybersecurity professional since most servers, tools, and attack environments run on Linux.

**Basic Linux Commands**
I learned and practiced the following core commands:
- `echo` — prints text to the screen
- `whoami` — shows the current logged-in user
- `ls` — lists files and folders in the current directory
- `cd` — changes directory
- `cat` — reads and displays the contents of a file
- `pwd` — prints the full path of the current working directory

**Searching for Content**
The `grep` command is used to search for specific text inside files. For example, running `grep "THM" access.log` searches the access.log file for any line containing "THM" — which is how flags are found in TryHackMe challenges.

**Shell Operators**
Linux shell operators control how commands behave:
- `>` — writes output to a file, replacing existing content
- `>>` — appends output to a file without deleting existing content
- `&` — runs a command in the background

**Key Takeaway:** Linux is the backbone of cybersecurity. Understanding how to navigate the file system, read files, search for content, and use shell operators are foundational skills that every security professional needs daily.

