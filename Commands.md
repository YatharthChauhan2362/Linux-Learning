# Commands

## Basic Commands

| Path     | Content                             |
| -------- | ----------


























------------------------- |
| `help`   | Shows you basic commands and use                         |
| `man`    | Shows you complete manual of that command or program                         |
| `ls`     | List all the folders and files of a directory                         |
| `cd`     | Change directory                         |
| `dir`    | Same as ls                       |
| `mkdir`    | Creates an directory                         |
| `cp`    | Copy a file or folder                         |
| `mv`    | Move a file or folder                       |
| `rm`    | Remove file or folder                        |
| `sudo su`   | Grant root privileges                         |
| `cat`   | Show content of a file                         |
| `nano`   | Linux file editor                        |
| `gedit`   | File editor software                         |
| `chmod`   | Change directory permission                         |
| `./`   | Execute shell file                         |
| `bash`   | Execute shell programs                         |
| `apt-get update`   | Update packages list (URL's)                         |
| `apt-get upgrade`   | Update all installed softwares                         |
| `apt-get install`   | Install a particular software                         |
| `top`   | Showing linux processes                         |
| `kill`   | Terminate processes Manually                         |
| `w`   | Who is logged on and what they are doing                         |
| `whoami`   | Display the username of the current user                         |
| `touch`   | Create empty files                         |
| `ifconfig`   | Show ip address                         |

# Basic Linux Commands

## Navigation Commands

- `pwd`: Print current working directory
- `ls`: List files and directories
  - `ls -l`: Detailed listing
  - `ls -a`: Show hidden files
- `cd`: Change directory
  - `cd <directory>`: Change to a specific directory
  - `cd ..`: Move up one directory
  - `cd ~`: Move to the home directory
- `mkdir`: Create a new directory
  - `mkdir <directory_name>`: Create a directory

## File Operations

- `touch`: Create an empty file
  - `touch <filename>`: Create a file
- `cp`: Copy files or directories
  - `cp <source> <destination>`: Copy source to destination
- `mv`: Move or rename files or directories
  - `mv <source> <destination>`: Move source to destination
  - `mv <old_filename> <new_filename>`: Rename a file
- `rm`: Remove files or directories
  - `rm <filename>`: Remove a file
  - `rm -r <directory>`: Remove a directory and its contents

## Viewing and Editing Files

- `cat`: Display the content of a file
- `more` or `less`: Display file content one screen at a time
- `nano` or `vim`: Text editors for creating and editing files

## Searching and Finding

- `grep`: Search for a pattern in files
  - `grep <pattern> <filename>`: Search for a pattern in a file
- `find`: Search for files and directories
  - `find <directory> -name <filename>`: Find a file in a directory

## System Information

- `uname`: Display system information
- `whoami`: Display the current username
- `df`: Show disk space usage
- `free`: Display free and used memory in the system

## User and Permissions

- `sudo`: Execute a command with superuser privileges
- `chmod`: Change file permissions
- `chown`: Change file ownership

## Process Management

- `ps`: Display information about active processes
  - `ps aux`: Display detailed information about all processes
- `kill`: Terminate a process
  - `kill <process_id>`: Terminate a process by ID

## Networking

- `ifconfig` or `ip`: Display network configuration
- `ping`: Check network connectivity
  - `ping <hostname or IP>`: Send ICMP echo requests to a host
- `netstat`: Display network statistics

## Compression and Archiving

- `tar`: Create and extract tar archives
  - `tar -cvf <archive_name.tar> <files>`: Create a tar archive
  - `tar -xvf <archive_name.tar>`: Extract files from a tar archive
- `gzip` or `gunzip`: Compress or decompress files
  - `gzip <filename>`: Compress a file# Basic Linux Commands

## Navigation Commands

- `pwd`: Print current working directory
- `ls`: List files and directories
  - `ls -l`: Detailed listing
  - `ls -a`: Show hidden files
- `cd`: Change directory
  - `cd <directory>`: Change to a specific directory
  - `cd ..`: Move up one directory
  - `cd ~`: Move to the home directory
- `mkdir`: Create a new directory
  - `mkdir <directory_name>`: Create a directory

## File Operations

- `touch`: Create an empty file
  - `touch <filename>`: Create a file
- `cp`: Copy files or directories
  - `cp <source> <destination>`: Copy source to destination
- `mv`: Move or rename files or directories
  - `mv <source> <destination>`: Move source to destination
  - `mv <old_filename> <new_filename>`: Rename a file
- `rm`: Remove files or directories
  - `rm <filename>`: Remove a file
  - `rm -r <directory>`: Remove a directory and its contents

## Viewing and Editing Files

- `cat`: Display the content of a file
- `more` or `less`: Display file content one screen at a time
- `nano` or `vim`: Text editors for creating and editing files

## Searching and Finding

- `grep`: Search for a pattern in files
  - `grep <pattern> <filename>`: Search for a pattern in a file
- `find`: Search for files and directories
  - `find <directory> -name <filename>`: Find a file in a directory

## System Information

- `uname`: Display system information
- `whoami`: Display the current username
- `df`: Show disk space usage
- `free`: Display free and used memory in the system

## User and Permissions

- `sudo`: Execute a command with superuser privileges
- `chmod`: Change file permissions
- `chown`: Change file ownership

## Process Management

- `ps`: Display information about active processes
  - `ps aux`: Display detailed information about all processes
- `kill`: Terminate a process
  - `kill <process_id>`: Terminate a process by ID

## Networking

- `ifconfig` or `ip`: Display network configuration
- `ping`: Check network connectivity
  - `ping <hostname or IP>`: Send ICMP echo requests to a host
- `netstat`: Display network statistics

## Compression and Archiving

- `tar`: Create and extract tar archives
  - `tar -cvf <archive_name.tar> <files>`: Create a tar archive
  - `tar -xvf <archive_name.tar>`: Extract files from a tar archive
- `gzip` or `gunzip`: Compress or decompress files
  - `gzip <filename>`: Compress a file
  - `gunzip <filename.gz>`: Decompress a file

## Miscellaneous

- `date`: Display wget or curl: Download files from the internet
wget <URL> or curl -O <URL>: Download a file
scp: Securely copy files between hosts
journalctl: Query and display messages from the journal (systemd)
shutdown or reboot: Shutdown or reboot the system
shutdown -h now: Shutdown immediately
reboot: Reboot the systemor set the system date and time
- `echo`: Display a message or variable value
- `history`: Display command history

  - `gunzip <filename.gz>`: Decompress a file
  
