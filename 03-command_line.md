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

> > * `pwd`   shows current working directory path
> > * `mkdir` creates a directory inside the working directory
> > * `rm -r` deletes a directory
> > * `touch` creates a new file inside the working directory
> > * `rm`    deletes a file
> > * `mv`    renames a file
> > * `ls -a` lists all files inside the working directory, including hidden files and directories
> > * `cp`    copies a file from one directory to another
> > * `cd`    switches into the specified directory
> > * `sort`  sorts lines of text alphabetically

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

> > * `ls`      lists all files and directories in the working directory
> > * `ls -a`   lists all contents of a directory including hidden files and directories
> > * `ls -l`   lists all contents of a directory in long format
> > * `ls -lh`  lists all contents of a directory in long format with readable file size
> > * `ls -lah` lists all contents of a directory including hidden files and directories in long format with readable file size
> > * `ls -t`   orders files and directories by the time they were last modified
> > * `ls -Glp` lists all contents of a directory in long format without group names and with / indicator appended to directories

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > * `ls -d` displays only directories
> > * `ls -m` displays the names as a comma-separated list
> > * `ls -R` displays subdirectories as well
> > * `ls -u` displays files by the access time
> > * `ls -t` displays newest files first (based on timestamp)

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > `xargs` reads data from standard input and executes the command (supplied to it as an argument) one or more times based on the input read.
> > If no command is supplied as an argument to xargs, the default command it executes is `echo`.
> > For example, if we wanted to search all .txt files in the current directory, we could use the following command: 
> > `xargs find -name`
> > then we would pass "\*.txt" as input through stdin by typing it and then tell `xargs` that we're done with the input by pressing `Ctrl+D`.
 

