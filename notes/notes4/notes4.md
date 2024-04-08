---
name: Pedro Hernandez 
course: cis106
semester: spring 2024
---

# Notes 4

### Wildcards.


### * Wildcard
The * matches anything and nothing and matches any number of characters
* Examples
  * Lists all files that end in a specific extension
    * `ls *.txt`
  * Lists more than one file in a dictionary
    * `ls *.txt *.pdf`
  * Lists all files that start with a specific word in a dictionary
    * `ls file.*`

### ? Wildcard
The ? matches precisely one character
* Examples
  * Lists all the files in the current dictatory (excluding hidden files)
    * `ls`
  * Lists all hidden files in the current directory
    * `ls ./.??*`
  * Lists all the hidden files in the parent directory
    * `ls ../.??*`
  
### [] Wildcard
The [] matches a single character in a range
* Example
  * To match all files that have a vowel after letter f
    * `ls f[aeiou]*`
  * To match all files that do not have a vowel after letter f
    * `la f[aeiou]*`
  * To match all files that have a range of letter after f
    * `ls f[a-z]*`
  
### {} Wildcard
The {} is not a wildcard but another feature of bash that allows you to generate arbitrary strings to use with commands
* Example
  * To create a whole dictionary structure in a single command
    * `mkdir -p music/{jazz,rock}/{mp3files,videos,oggfiles}/new{1..3}`
  * To create a N number of files use
    * `touch website{1..5}.html`
    * `touch file{A..Z}.txt`
  * To remove multiple files in a single directory
    * `rm -r {dir1,dir2,dir3,file.txt,file.py}`

