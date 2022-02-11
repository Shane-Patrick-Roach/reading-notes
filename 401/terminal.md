# Terminal
---

## What is the terminal exactly?

- A command line, or terminal, isa text based interface to the system.
- You are able to enter commands by typing them on the keyboard and feedback will be given to you similarily as text.


## What is the shell?

- This is the part of the operating system that defines how the terminal will behave and looks after running commands for you.
- Various shells exist. **bash** stands for Bourne again shell.



## List of commands
-  PWD = Present working directory
- ls = short for list, lists contents of a directory
- cd - change directory - move to another directory 



## Paths 

- Two types of paths we can use. Absolute or Relative.
- Absolute paths specify a locaation in relation to the root directory. Identify them easily as they always begin with a forward slash (/)
- relative paths specify a location in realtion to where we currently are in the system. They will not begin with a slash.


## Linux is an Extensionless System

- A file extension is normally a set of 2-4 characters after a full stop at the end of a file, which denotes what type of file it is. Common extensinons include => file.exe, file.text, file.png, file.gif, etc...

## Important notes on files

- Linux is case sensitive
- Spaces in names
- Hidden files and directories
- File => obtain information about what type of file a file or directory is.
- ls -a => List the contents of a directory, including hidden files.
- Everything is a file under Linux.
- Linux is an extionless system, files can have any extention they like or none at all.


## What are the Manual Pages?
---

- The manual pages are a set of pages that exlpain every command available on your system including what they do.
- You invoke the manual pages with the following command. `man <command to look up>`
- To exit the man pages, press `q`
- **The main pages are your friend**, instead of trying to remember everything, instead remember you can easily look stuff up in the man pages.



## File Manipulation
---

### Making a directory

- `mkdir [options] <Directory>`
- short for making a directory

### Removing a directory

- `rmdir [options] <Directory>`
- A directory must be empty before it can be removed.

### Creating a blank file

- `touch [options] <dfilename>`


### copying a file or directory

- `cp[options] <source><destination>`
- note that source and destination aare paths. This means we may refer to them using both absolute and relative paths. Example => `cp /home/ryan/lunuxtutorial/example2 example3`
- using -r option, which stands for recursive, we may copy directories. Recursive means that we want to look at a directory and all the files and directories with it, and for subdirectories, go into them and do the same thing and keeping doing this.

### Moving a file or directory

- `mv[options] <source><destination>`


### Important takeaways from moving files

- No undo => the linux command line does not have an undo feature. Perform destructive actions carefully.
- Most commands have many useful line options. Make sure to skim the man page for new commands so you are familiar with what they can do and whaat is available.

## Link to Useful Resouces

[Cheat Sheet]('https://ryanstutorials.net/linuxtutorial/cheatsheet.php')
