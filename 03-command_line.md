# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)   


| Command | Descrption |
| ------ | ------ |
| `pwd`   | show current working directory path|
| `cp `  | copying a file from one directory to another|
| `mv > new.file `  | renaming a file|
| `rm `     | delete a file|
| `rmdir`   | deleting a directory (delete files first)|
| `mkdir `  | creating a directory|
| `touch `| creating a file using `touch` command|
| `touch -c` |if the file does not exist, do not create it |
| `ls -la`   | list contents, long format include hidden files|
| `cat` | view content of a file|
| `less` | view content piece by piece|
| `head` | preview of a file by Rows from the beginning|
| `head -n` | specify # of rows|
| `tail`| preview of a file by Rows from the end|
| `tail -n +N -N`| from Nth row, counting from the beginning + or from the end -|
| `cut` | Select columns|
| `cut -f` | Specify fields/columns |
| `cut -d` | Specify delimiter|
| `grep` | Search files/Select files |
| `wc` | Count lines, words, characters|
| `sort` | Sort, default order is ascending|
| `sort -r` | Reverse |
| `sort -n` | Numerical |
| `uniq` | Remove **adjacent** duplicates (sort first) |
| ?, [], {} | Wild Cards. Brackets: Any char, any word |

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  


| Command       |  Description  |
| ------------- | ------------- |
| `ls`          | list directory content   |
| `ls -a`       |   include entries whose name start with a dot (.) |  
| `ls -l`       |   list in long format providing file mode, number of links owner name, group name, size, abbreviated month, day of month/hour/minute file was modified, and the pathname  | 
| `ls -lh`      |  |
| `ls -lah`     |  |
| `ls -t`       |  sort by time modified (recent first)  |  
| `ls -Glp`     | list: colorized output, long format, with trailing slash for dirs |



---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

| Command       |  Description  |
| ------------- | ------------- |
| `ls -1`          | display all in 1 column   |
| `ls -R `  | Recursively list all underlying dirs  |
| `ls -d `  |  Display only directories |
| `ls -G1p `  |  Display in one column, Colorize and add / to dirs |
| `ls -o `  | Same as `la -l` but not groupname  |

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > echo is the default response if nothing specified
-n N

---

### Grep command
| grep flags |  Description |
| ------------- | ------------- |
|-c | print a count of matching lines rather than the lines themselves  |
|-h | do not print the names of files when searching multiple files  |
|-i | ignore case (e.g., treat "Regression" and "regression" as matches)  |
|-l | print the names of files that contain matches, not the matches  |
|-n | print line numbers for matching lines  |
|-v | invert the match, i.e., only show lines that don't match  |

