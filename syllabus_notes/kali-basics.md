# Kali Basics

### ls: Lists all files or directories
  | Command | Function |
  |---------|----------|
  |   ls ./path, |    List out the contents of a specific directory  |
  |   ls ..   |  List our the contents of the parent directory    |
  |   ls ~   |  List our the contents of the user's home directory    |
  |   ls -d */  |  List directories only    |
  |   ls *  |  List directories and sub directories   |
  |   ls -l  | List directories or files showing permissions, ownership, etc..   |
  |   ls -a  | List directories or files including hidden ones  |
  | ls -la |  List directories or files including hidden ones in long format  |
  |   ls > output_file.txt   |    Print list contents to the created file      |


### pwd
  - Shows standard output of the full path name of current directory

### grep
| Command | Function |
|---------|----------|
| grep "text" file.txt | Search for the text within the text file. Will count partials |
| grep -i "text" file.txt |   Removes case sensitive   |
| grep -w "text" file.txt |   Strict match the string  |
| grep -n "text" file.txt |   Will show line match was found on  |
| grep -A {#} "text" file.txt |   Shows given number of lines before match   |
| grep -B {#} "text" file.txt |   Shows given number of lines after match  |
| grep -C {#} "text" file.txt |   Shows given number of lines before and after match   |
| grep -win ./* | will search entire directory   |


| Command | Function | Flags |  Example |   |
|---------|----------|-------|---|---|
|   ls      |    List all files or directories      |       |   |   |
|   pwd    |          |       |   |   |
|   cd      |          |       |   |   |
|   dir      |          |       |   |   |
|   mkdir     |          |       |   |   |
|   touch     |          |       |   |   |
|   grep    |          |       |   |   |
