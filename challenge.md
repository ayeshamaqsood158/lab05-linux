# Lab 05 Challenge: Security Detective
## Question 1
Answer: I am logged in as the user `student`. My home folder is `/home/student`.
Commands: `whoami`, `pwd`
## Question 2
Answer: The server's name is `ubuntu-lab01`. It runs Ubuntu 24.04.3 LTS.
Commands: `hostname`, `cat /etc/os-release`
## Question 3
Answer: The server has 1.9Gi of RAM. It has 4.0G of free disk space.
Commands: `free -h`, `df -h /`
## Question 4
Answer: The users who can log in with /bin/bash are `root` and `student`.
Commands: `grep /bin/bash /etc/passwd`
## Question 5
Answer: There are 115 processes running right now.
Commands: `ps aux | wc -l`
## Question 6
Answer: The user `lab5user` was created at 10:15:00 and deleted at 10:30:00.
Commands: `sudo grep lab5user /var/log/auth.log`
