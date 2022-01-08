# VAPT CHEATSHEET
## KALI LINUX COMMANDS
Sudo su:
To get root folder access in COMMAND LINE


Pwd: Present working directory

### slash-commands
  > want to go to the top most folder(node) from anywhere in the pwd: [CLick Here](https://github.com/sagar98cyber/vapt/tree/slash-command)

### chmod-commands
  > to change the permissions of a file or a directory: [CLick Here](https://github.com/sagar98cyber/vapt/tree/chmod-branch)

### '../' operator to go one folder above the current pwd

### '~' -operator(tilde-operator or ROOT LOCATION Operator)
  > to enter the root folder from any pwd: [CLick Here](https://github.com/sagar98cyber/vapt/tree/tilde-operator)

### 'ls -al' to look for the hidden folders
  
### 'cp' copy command
  > to copy file from one location to another: [CLick Here](https://github.com/sagar98cyber/vapt/blob/main/copy-command.PNG)
    
### 'mv' move command
  > to move a file or a folder from one folder to another: [CLick Here](https://github.com/sagar98cyber/vapt/blob/main/move-command.PNG)

### 'rm' to remove a specific file

### 'updatedb' to update the database for searching a file or for 'locate' command to look for a file
  > if looking for a file and the file doesnot appear updatedb to update database: [CLick Here](https://github.com/sagar98cyber/vapt/blob/main/updatedb-command.PNG)

### 'locate' command to look for a file in database
  > to look for a file in database: [CLick Here](https://github.com/sagar98cyber/vapt/blob/main/locate.PNG)

### how to identify if the entry in 'ls -al' is a file or a directory
> if it shows 'd' as a prefix of a file then it is a directory if it displays a '-' then it is a file: [CLick Here](https://github.com/sagar98cyber/vapt/blob/directory-file-identification/directory%20and%20file%20diff.png)

### 'adduser' to create a new user
> to create a new user use "adduser <user-name>": [CLick Here](https://github.com/sagar98cyber/vapt/blob/users-commands/ADD%20USER%20AND%20CHECK%20ETC%20PASSWD.PNG)

### 'cat /etc/psswd'
> 'cat /etc/psswd' to view every user present on the system: [CLick Here](https://github.com/sagar98cyber/vapt/blob/users-commands/ADD%20USER%20AND%20CHECK%20ETC%20PASSWD.PNG)

### 'cat /etc/shadow'
> 'cat /etc/shadow' to access password of every user present on the system. Using any tool like HASHCAT to break the password.

### su <user-name>
> 'su john' to switch to user john present on the system

### 'sudo passwd root'
> to change of the password of the user present on the system <br>
>Note: The command only works if you have sudoers access to the user, if not use 'sudo su' to get the sudoers access

### ifconfig
> this command tells you the network configuration of the network for the ethernet

### iwconfig
> this command tells you the network configuration of the network for the wireless adapter

### arp -a
> this commands shows IP ADDRESS it talks to and the corresponding MAC ADDRESS

### netstat -ano
> this commands shows active connections running on the machine

### route
> this commands shows the routing table on the device

### FILE COMMANDS
> [Click Here](https://github.com/sagar98cyber/vapt/blob/file-commands/FILE%20COMMANDS.png)

## NOTES:
### TTL - TIME TO LIVE
>TTL for windows is 128 <br>
>TTL for Linux is 64