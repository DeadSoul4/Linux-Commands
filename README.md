# 🐧 Linux Commands  

This repository contains a curated list of useful Linux commands and shell scripts for everyday use, system management, and automation.

## 🚀 Commands Included  

### 1️⃣ **Navigating Directories**  
- `cd <directory>`: Change to a specific directory.
- `ls`: List files and directories.
- `pwd`: Print the current working directory.
- `mkdir <dir_name>`: Create a new directory.

### 2️⃣ **File Management**  
- `cp <source> <destination>`: Copy files or directories.
- `mv <source> <destination>`: Move or rename files.
- `rm <file_name>`: Remove files or directories.
- `touch <file_name>`: Create a new empty file.

### 3️⃣ **File Viewing and Editing**  
- `cat <file_name>`: View the contents of a file.
- `less <file_name>`: View files one page at a time.
- `nano <file_name>`: Edit a file using the nano text editor.
- `vim <file_name>`: Edit a file using the Vim editor.

### 4️⃣ **Search Commands**  
- `grep <pattern> <file_name>`: Search for a pattern within a file.
- `find <directory> -name <file_name>`: Search for a file by name.
- `locate <file_name>`: Locate a file quickly in the system.

### 5️⃣ **Permissions and Ownership**  
- `chmod <permissions> <file_name>`: Change file permissions.
- `chown <owner>:<group> <file_name>`: Change file owner and group.

### 6️⃣ **System Information**  
- `top`: Display running processes.
- `df -h`: Check disk space usage.
- `free -m`: Display memory usage.
- `uname -a`: Show system information.

### 7️⃣ **Networking**  
- `ping <hostname>`: Check network connectivity.
- `ifconfig`: Display network interfaces and IP addresses.
- `netstat -tuln`: Display listening ports.
- `curl <url>`: Fetch data from a URL.

### 8️⃣ **Process Management**  
- `ps aux`: Show currently running processes.
- `kill <PID>`: Kill a process by its PID.
- `top`: Monitor active processes in real-time.

### 9️⃣ **Disk Management**  
- `lsblk`: List all block devices.
- `mount <device> <directory>`: Mount a file system.
- `umount <device>`: Unmount a file system.

### 🔟 **Shell Scripting Examples**  
- Create a basic shell script to automate tasks like backups, system updates, or file management.

```bash
#!/bin/bash
# A simple script to back up a directory
tar -czvf backup.tar.gz /home/user/documents/
