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

`pwd: show current working directory path`  
`mkdir: creating a directory`   
`rm -r: deleting a directory`  
`touch: create a file`  
`rm: deleting a file`  
`mv: renaming a file`  
`ls -a: listing hidden files`  
`cp dirA\file dirB: copying a file from one directory to another`  
`vi: edit a file`  
`chown: changing ownership of a file/directory`  
`chmod: changing permission of a file/directory`  

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

> > 
`ls: listing files/directories under current working directory path`   
`ls -a: listing all files/directories including the hidden ones (name starting with .)`  
`ls -l: listing files/directories with a long format`  
`ls -lh: listing files/directories size in human readable format`  
`ls -lah: listing all files/directories with a long format including the hidden ones`    
`ls -t: listing all files/directories in a reverse chorological order`  
`ls -Glp: listing all files/directories in a colored format and directories are marked with /`  

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 
`-b	Displays nonprinting characters in octal.`  
`-i	Displays the inode for each file.`  
`-n	Displays the long format listing, with GID and UID numbers.`  
`-R	Displays subdirectories as well.`  
`-u	Displays files by the file access time.`  

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > Xargs reads data from standard input (stdin) and executes the command (supplied to it as an argument) one or more times based on the input read. [Source](https://www.howtoforge.com/tutorial/linux-xargs-command/) 

```console
DN0a2324ab:~ songlin$ xargs find . -name
"*.txt"./Music/Audio Music Apps/Plug-In Settings/Alchemy/Libraries/ImportBrowser/Favorites.txt
./MS&E 267/Project/selenium-route-eval/node_modules/immediate/LICENSE.txt

```

 

