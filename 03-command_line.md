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

`pwd` show current working directory path
`mkdir` creating a directory
`rm -r` deleting a directory
* creating a file using `touch` command
`rm` deleting a file
`mv oldname newname` renaming a file
`ls -a` listing hidden files
`cp filename destination` copying a file from one directory to another
`cd` change directory
`echo` you can write a file for example - echo 'Hello' > hello.txt 
`cat file1.txt > file2.txt` redirect the standard output from one file to another
`cat file1 file2 file3 > file4` will concatenate content from files 1, 2 and 3, and redirect to file 4

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

`ls` lists the files and folders inside the folder you are in
`ls -a`  lists all files and folders in the working directory, including hidden files (hidden files starts with a .)
`ls -l`  lists all content in the working directory in long format
`ls -lh` lists content in the working directory, and displays its files size in long format
`ls -lah`  lists content in the working directory, and displays its files size in long format, including hidden files information
`ls -t` order files in the directory by the time they were last modified 
`ls -Glp` lists content in the working directory in long format, don't print group name

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

ls -lh
ls -p
ls -la
ls -1
ls -S
ls -1

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

`xargs` reads data from input and executes it.
`echo` is the default command executed by `xargs`
for example, we can use the following command to find txt files
`xargs find -name "*.txt"`
 
