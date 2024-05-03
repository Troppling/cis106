---
name: pedro hernandez
course: cis106
semester: spring 24
---

# Notes 5

## Cat command
### Definition
The cat command is used to display the contents of a file. The word cat is shortened for concentrate which is the intended use of this command
### Usage 
`cat` + `option` + `files to display`
### Examples
* Display the contents of a file located in the pwd
  * `cat todo.lst`
* Display the content of a file using absolute path
  * `cat ~/Documents/todo.lst`


## Tac Command
### Definition
The tac command is used for displaying the content of a file in reverse order.
### Usage
`tac + option + files to display`
### Examples
* Display the content of a file located in pwd
  * `tac todo.md`
* Display the content of a file using absolute path
  * `tac ~/Documents/todo.md`


## Head command
### Definition
The head command displays the top N number of lines of a given file. By default it prints the first 10 lines.
### Usage
`head + option + files`
### Examples
* Display the first 10 lines of a file
  * `head ~/Documents/Book/dracula.txt`
* Display the first 5 lines of a file
  * `head -5 ~/Documents/Book/dracula.txt`


## Tail command
### Definition
The tail command displays the last N number of lines of a given file. It prints the last 10 lines by default
### Usage
`tail + option + file`
### Examples
* Display the last 10 lines of a file
  * `tail ~/Documents/Book/dracula.txt`
* Display the last 5 lines of a file
  * `tail -5 ~/Documents/Book/dracula/txt`


## Cut command
### Definition
The cut command is used to extract a specific section of each line of a file and display it to the screen
### Usage
`cut + option + file's`
### Examples
* Display a list of all the users in your system
  * `cut -d ':' -f1 /etc/passwd`
* Display a list of all the users in your system with their login shell
  * `cut -d ':' -f1,7 /etc/passwd`


## Sort command
### Definition
The sort command is used for sorting files. The sort command support sorting alphabetically, in reverse order, by number, and by month
### Usage
`sort + option + file`
### Examples
* Sort a file and save the output to a new file
  * `sort -o sorted.lst users.lst`
* Sort a file in reverse order
  * `sort -r users.txt`


## WC command
### Definition
The wc command is used for printing the number of lines
### Usage
`wc + option + files's`
### Examples
* Display the number of characters in a file
  * `wc -m users.txt`
* Display the number of lines in a file
  * `wc -l users.txt`


## Diff Command
### Definition
The diff command compares files and displays the differences between them
### Usage
`diff + option + file1 +file2`
### Examples
* Display the difference between two files
  * `diff cars.csv cars-backup.csv`
* Display the difference between two files ina column format
  * `diff -y cars.csv cars-backup.csv`


## Grep Command
### Definition
The grep command is used to search text in a given file. 
### Usage
` grep + option + search criteria +files`
### Examples
* Search any line that contains the work 'dracula' in the given file
  * `grep 'dracula' ~/Documents/dracula.txt`
* Search for all the lines that do not contain the word 'war'
  * `grep -v 'war' ~/Documents/Books/war-and-peach.txt`



