# Lab 1 – Linux System Navigation

## Objective
Practice navigating the Linux file system and inspecting important directories used in system administration.

## Environment
Ubuntu running inside VirtualBox.

## Commands Practiced

### pwd
Displays the current working directory.

Screenshot:

![pwd output](screenshots/pwd1.png)
### ls
Lists files and directories.
![ls command output](screenshots/ls.jpeg)
ls -la
Lists files including hidden files and permissions.
![ls la command output](screenshots/lsla.png)

cd /etc
Navigates to the system configuration directory.
![ls la command output](screenshots/cdetc.png)
![ls la command output](screenshots/cdetc2.png)
![ls la command output](screenshots/cdetc3.png)
![ls la command output](screenshots/cdetc4.png)
cd /var
Navigates to variable system data such as logs.

cd ~
Returns to the user's home directory.

## Key Directories Explored

/etc  
Contains system configuration files.

/home  
Contains user home directories.

/var  
Stores logs, application data, and temporary files.

## What I Learned

Understanding the Linux filesystem hierarchy is essential for troubleshooting servers, locating configuration files, and inspecting system logs.
