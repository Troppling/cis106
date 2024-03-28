## Commands for Creating files and directories

## The mkdir command
### Definition:
is used for creating a single directory or multiple directories
### Usage:
`mkdir` + `the name of the directory`
### Examples:
* To create a directory in the present working directory
  * `mkdir` `wallpapers`
* Create a directory in a different directory using relative path
  * `mkdir` `wallpapers/ocean`
* Create a directory in a different directory using absolute path
  * `mkdir` `~wallpapers//forest`


## The touch Command
### Definition:
used for creating files
### Usage:
`touch`
### Examples:
* To create a file called list
  * `touch` `list`
* To create several files
  * `touch` `list_of_cars.txt script.py names.csv`
* To create a file using absolute path
  * `touch` `~/Downloads/games.txt`
  

### The rm Command
### Definition:
The rm command removes files
### Usage:
`rm`
### Examples:
* Remove a file
  * `rm` `list`
* Remove a file and prompt confirmation before removal
  * `rm` `-i` `list`
* Remove all the files inside a directory and ask before removing more than 3 files
  * `rm` `-I` `Downloads/games/*`


## The rmdir Command
### Definition:
used to remove directories
### Usage:
`rmdir`
### Examples:
* To remove an empty directory
  * `rmdir` `Downloads/games`


## The mv Command
### Definition:
moves and renames directories
### Usage:
`mv` + `source` + `destination`
### Examples:
* To move a file from a directory to another using relative path
  * `mv` `Downloads/homework.pdf Documents/`
* To move a directory from one directory to another using absolute path
  * `sudo mv` `~Downloads/theme` `/usr/share/themes`
* To move a file from one directory to another combining absolute and relative path
  * `mv` `Downloads/english_homework.docx` `/media/student/flashdrive/`


## The cp Command
### Definition:
copies files/directories from a source to a destination
### Usage:
`cp` + `files to copy` + `destination`
### Examples:
* To copy a file
  * `cp` `Downloads/wallpapers.zip` `Pictures/`
* To copy a directory with a absolute path
  * `cp` `-r` `~/Downloads/wallpapers` `~/Pictures`
* To copy the content of a directory to another directory
 * `cp` `Downloads/wallpapers/*` `~/Pictures/`


## The file command
### Definition:
determines the file type of a file
### Usage:
`file` + `filename`
### Examples:
* Display file type without file name
  * `file` `-b` `filename`


## The pdinfo Command
### Defination:
displays information about pdf files
### Usage:
`pdinfo` `filename.pdf`


## The mediainfo Command
### Definition:
command line utility to display information about audio/video files
### Usage:
`mediainfo`
### Examples:
* Display information about a media file
  * `mediainfo` `example.png`
* Display full information of a media file
  * `mediainfo` `-f` `example.png`


## The exiv2 Command
### Definition:
image metadata manipulation tool
### Usage:
`exiv2` `option` `action` `file`
### Examples:
* Displays information about an image file
  * `exiv2` `example.png`
* Displays all exif data about an image file
  * `exiv2` `-pt` `example.png`


## The exiftool Command
### Definition:
read and write meta information files
### Usage:
`see man page`
### Examples:
* Displays information about a file
  * `exiftool` `example.png`


