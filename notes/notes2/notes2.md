## Each of the commands used for navigating the file system

## Pwd Command
### Definition:
Displays the absolute path of the current working dictionary
### Usage:
`pwd`  
### Examples:
* To display the current working dictionary
  `pwd`


## Cd Command
### Definition:
Changes the current working dictionary. In other words to move you around
### Usage:
`cd` + `Destination`
### Examples:
* To change from your home dictionary to your Downloads dictionary
  * `cd Downloads`
* To change from anywhere in the file system to Downloads
  * `cd` `~/Downloads`
* To change from anywhere in your file system to your Documents dictionary
  * `cd` `/home/$USER/Documents`


## Ls Command
### Definition:
Lists the contents of a given dictionary or file/dictionary itself.
### Usage:
`ls` + `option` + `dictionary to list`
### Examples:
* Lists the content of the present working dictionary
  * `ls`
* List all the files inside the current working dictionary including hidden files
  * `ls -a`
* List all the files inside a given dictionary
  * `ls -a ~/Pictures`
  

## Definition of Words
### File System:
* The way files are stored and organized

### Pathname
* The pathname is the name of the file which indicates the location of the file in the file system

### Absolute path
* The location of a file starting in the root od the file system

### Relative Path
* The location of a file starting from the current working dictionary or a dictionary that is located inside the current working dictionary

### Difference between "Your home dictionary" and "The home dictionary"
**Your Home Dictionary** refers to your user's home dictionary
#### Example:
  * /home/adrian is the home dictionary of the user adrian

**The Home Dictionary** refers to the home dictionary located in the root.
#### Example:
  * /home
  
### Parent Dictionary
* A dictionary containing one or more dictionaries and files

### Child Dictionary
* This is a dictionary inside another dictionary

### Bash Special Characters
* Functions like a command that tell the shell to perform a specific action without having to type the complete command.

### Environment Variables
* stores values of a user's environment and can be used in commands in the shell

### User Defined Variables
* created by the user and exist only in the script and subshell that runs the script

### Why do we use $ with variables in bash shell scripting
* We use variables to allows us to temporarily store information within the shell script for use with other commands in the script



