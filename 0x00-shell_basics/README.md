# Introduction
Alx software engineering project to master shell basics. Below are the tasks and solutions.

## Requirements
### General
- Allowed editors: vi, vim, emacs
- All your scripts will be tested on Ubuntu 20.04 LTS
- All your scripts should be exactly two lines long ($ wc -l file should print 2)
- All your files should end with a new line (why?)
- The first line of all your files should be exactly #!/bin/bash
- A README.md file at the root of the repo, containing a description of the repository
- A README.md file, at the root of the folder of this project, describing what each script is doing
- You are not allowed to use backticks, &&, || or ;
- All your scripts must be executable. To make your file executable, use the chmod command: chmod u+x file. Later, we’ll learn more about how to utilize this command.

### 0. Where am i?
A script that prints the absolute path of the current working directory. [0-current_working_directory](./0-current_working_directory)

### 1. What is in there?
Script to display the contents list of your current directory. [1-listit](./1-listit)

### 2. There is no place like home
Write a script that changes the working directory to the user's home directory.
- You are not allowed to use any shell variables. [2-bring_me_home](./2-bring_me_home)

### 3. The long format
Display current directory contents in a long format. [3-listfiles](./3-listfiles)

### 4. Hidden files
Display current directory contents, including hidden files (starting with .). Use the long format. [4-listmorefiles](./4-listmorefiles)

### 5. I love numbers
Display current directory contents.
- Long format
- with user and groups IDs displayed numerically
- and hidden files (starting with .). [5-listfilesdigitonly](./5-listfiledigitonly).

### 6. Welcome
Create a script that creates a directory named ***my_first_directory*** in the ***/tnp/*** directory. [6-firstdirectory](./6-firstdirectory)

### 7. Betty in my first directory
Move the file ***betty*** from ***/tmp/*** to ***/tmp/my_first_directory***. [7-movethatfile](./7-movethatfile)

### 8. Bye bye Betty
Delete the file ***betty***
- The file ***betty*** is in ***/tmp/my_first_directory***. [8-firstdelete](./8-firstdelete)

### 9. Bye bye My first directory
Delete the directory ***my_first_directory*** that is in the ***/tmp*** directory. [9-firstdirdeletion](./9-firstdirdeletion)

### 10. Back to the future
Write a script that changes the working directory to the previous one. [10-back](./10-back)

### 11. Lists
Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the ***/boot*** directory (in this order), in long format. [11-lists](./11-lists)
