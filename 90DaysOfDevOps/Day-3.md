# Day-3 Task :🐧Linux Commands Cheat Sheet

1. PROCESS MANAGEMENT

       |      Command      |         Description          |
       | ----------------- | ---------------------------- |
       | `ps`              | Show current shell processes |
       | `ps -e`           | Show all running processes   |
       | `ps aux`          | Detailed process info        |
       | `top`             | Real-time process monitoring |
       | `htop`            | Advanced interactive monitor |
       | `kill PID`        | Terminate process            |
       | `kill -9 PID`     | Force kill                   |
       | `pkill name`      | Kill by process name         |
       | `bg`              | Resume process in background |
       | `fg`              | Resume in foreground         |
       | `jobs`            | Show background jobs         |
       | `nice -n 10 cmd`  | Start with priority          |
       | `renice -n 5 PID` | Change priority              |
       ----------------------------------------------------
   
2. FILE SYSTEM

       |      Command      |      Description       |
       | ----------------- | ---------------------- |
       | `ls`              | List files             |
       | `ls -l`           | Long listing           |
       | `ls -a`           | Show hidden files      |
       | `pwd`             | Current directory      |
       | `cd /path`        | Change directory       |
       | `tree`            | Directory structure    |
       | `touch file`      | Create empty file      |
       | `cp a b`          | Copy file              |
       | `cp -r dir1 dir2` | Copy directory         |
       | `mv a b`          | Move / rename          |
       | `rm file`         | Delete file            |
       | `rm -r dir`       | Delete directory       |
       | `mkdir dir`       | Create directory       |
       | `rmdir dir`       | Delete empty directory |
       | `cat file`        | View content           |
       | `less file`       | Scroll view            |
       | `head -n 10 file` | First 10 lines         |
       | `tail -n 10 file` | Last 10 lines          |
       | `tail -f file`    | Live logs              |
       ----------------------------------------------
   
3. NETWORKING & TROUBLESHOOTING

        |         Command         |       Description        |
        | ----------------------- | ------------------------ |
        | `ip a`                  | Show IP addresses        |
        | `ip r`                  | Routing table            |
        | `ifconfig`              | Network interfaces (old) |
        | `hostname`              | System hostname          |
        | `hostname -I`           | IP address               |
        | `ping google.com`       | Check connectivity       |
        | `traceroute google.com` | Packet path              |
        | `tracepath`             | Lightweight traceroute   |
        | `mtr google.com`        | Ping + traceroute        |
        | `netstat -tuln`         | Open ports               |
        | `ss -tuln`              | Modern netstat           |
        | `lsof -i :80`           | Who using port 80        |
        | `nmap ip`               | Scan ports               |
        | `nslookup google.com`   | DNS lookup               |
        | `dig google.com`        | Detailed DNS             | 
        | `resolvectl status`     | DNS resolver             |
        ------------------------------------------------------
