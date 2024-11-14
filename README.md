# GNU and Unix commands
## Getting System Information  
-To print your current directory use ***pwd***  
```bash
pwd
```
**touch**: Command to update the timestamps on existing files and also used to create new files  
```bash
touch file
touch file.txt
```
**uname**: Displays information about the linux system you are running like the linux kernel version that is currently loaded.
```bash
#to display the name of the O.S.
uname
#to print the machine hardware name
uname -m
#to  print the currently loaded linux kernel version  
uname -c
uname -s
uname --kernel-name
```
**man**:Is an interface to the system's reference manuals.
```bash  
man <command>
```
**apropos**:Helps you search through the man pages and description for instances of keyword.  
```bash
apropos apropos
#searches the man pages for apropos
```
**type**: Gives basic data about a command
```bash
type uname
```
**which**: returns the absolute location of a command
