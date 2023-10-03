# OS EX.4-LINUX-COMMANDS

## AIM:
To explore and implement the fundamentals of UNIX commands.
## Software requirements:
1. Linux operating system

## Linux Commands


### COMMAND1:ls - List Directory Contents
```
Syntax:
ls [options] [directory]

Code:
ls -l /path/to/directory

Output:
Lists the contents of the specified directory in long format, displaying permissions, owner, group, size, and modification date of files and subdirectories.

```
### Command 2: cd - Change Directory
```
Syntax:
cd [directory]

code:
cd /path/to/directory

Output:
Changes the current working directory to the specified directory.

```

### Command 3: pwd - Print Working Directory
```
Syntax:
pwd

Code:
pwd

Output:
Displays the current working directory, showing the full path.

```
### Command 4: mkdir - Create Directory
```
Syntax:
mkdir [options] [directory]

Code:
mkdir new_directory

Output:
Creates a new directory with the specified name.

```
### Command 5: touch - Create Empty File
```
Syntax:
touch [filename]
Code:
touch newfile.txt
Output:
Creates an empty file with the given name.
```
### Command 6: cp - Copy Files and Directories
```
Syntax:
cp [options] source destination

Code:
cp file.txt /path/to/destination/

Output:
Copies the specified file to the destination directory.

```
### Command 7: mv - Move or Rename Files and Directories
```
Syntax:
mv [options] source destination

Code:
mv oldfile.txt newfile.txt

Output:
Renames the "oldfile.txt" to "newfile.txt" or moves files and directories between locations.

```

### Command 8: rm - Remove Files and Directories
```
Syntax:
rm [options] [file/directory]

Code:
rm file.txt

Output:
Deletes the specified file.

```
### Command 9: cat - Concatenate and Display File Content
```
Syntax:
cat [options] [file]

Code:
cat myfile.txt

Output:
Displays the contents of the specified file.

```
### Command 10: less - View File Content Page by Page
```
Syntax:
less [file]

Code:
less largefile.log

Output:
Allows you to view large file contents one page at a time.

```
### Command 11: head - Display the Beginning of a File
```
Syntax:
head [options] [file]

Code:
head -n 10 myfile.txt

Output:
Displays the first 10 lines of the specified file.

```
### Command 12: tail - Display the End of a File
```
Syntax:
tail [options] [file]

Code:
tail -n 20 logfile.log

Output:
Displays the last 20 lines of the specified file, typically used for log files.

```
### Command 13: grep - Search Text in Files
```
Syntax:
grep [options] 'pattern' [file(s)]

Code:
grep 'searchterm' file.txt

Output:
Searches for the specified pattern in the given file(s).

```
### Command 14: find - Search for Files and Directories
```
Syntax:
find [path] [options] [expression]

Code:
find /path/to/search -name "myfile.txt"

Output:
Searches for files and directories based on specified criteria within the given path.

```
### Command 15: tar - Archive and Compress Files
```
Syntax:
tar [options] [archive-file] [files/directories]

Code:
tar -cvzf archive.tar.gz directory/

Output:
Creates a compressed archive of files and directories.
```
### Command 16: unzip - Extract Compressed Files
```
Syntax:
unzip [options] [compressed-file]

Code:
unzip archive.zip

Output:
Extracts files from a compressed archive.
```
### Command 17: ps - List Running Processes
```
Syntax:
ps [options]

Code:
ps aux

Output:
Lists the currently running processes along with their details.

```
### Command 18: top - Display Dynamic System Statistics
```
Syntax:
top

Code:
top

Output:
Displays real-time system statistics, including CPU usage, memory usage, and running processes.

```
### Command 19: chmod - Change File Permissions
```
Syntax:
chmod [options] permissions file(s)

Code:
chmod 755 myfile.sh

Output:
Modifies file permissions to control read, write, and execute access.

```
### Command 20: chown - Change File Ownership
```
Syntax:
chown [options] user:group file(s)

Code:
chown user:group myfile.txt

Output:
Changes the ownership of files and directories to the specified user and group.

```
### Command 21: sudo - Execute a Command with Superuser Privileges
```
Syntax:
sudo [command]

Code:
sudo apt-get update

Output:
Allows the execution of a command as a superuser or with elevated privileges.
```
### Command 22: df - Display Disk Space Usage
```
Syntax:
df [options]

Code:
df -h

Output:
Displays information about disk space usage, including available and used space on mounted file systems.
```
### Command 23: du - Display File and Directory Space Usage
```
Syntax:
du [options] [directory]

Code:
du -sh /path/to/directory

Output:
Shows the disk space used by files and directories.
```
### Command 24: uptime - Display System Uptime
```
Syntax:
uptime

Code:
uptime

Output:
Shows how long the system has been running since the last reboot.
```
### Command 25: wget - Download Files from the Internet
```
Syntax:
wget [options] [URL]

Code:
wget https://example.com/file.zip

Output:
Downloads "file.zip" from the specified URL.
```
### Output
![](https://github.com/RanjithD18/EX.4-LINUX-COMMANDS/blob/main/1.jpeg)
![](https://github.com/RanjithD18/EX.4-LINUX-COMMANDS/blob/main/2.jpeg)
![](https://github.com/RanjithD18/EX.4-LINUX-COMMANDS/blob/main/3.jpeg)
![](https://github.com/RanjithD18/EX.4-LINUX-COMMANDS/blob/main/4.jpeg)
### Result
This implies that you have acquired a foundational understanding of UNIX commands and have successfully carried out their execution.
