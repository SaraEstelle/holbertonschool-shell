Shell, Basics
Holberton School – System Engineering & DevOps


📘 Overview
This project introduces the foundations of the shell, command‑line navigation, and basic file manipulation in a Unix environment.
It is the first step in the System Engineering & DevOps track and teaches you how to interact with your system using Bash instead of a graphical interface.

All requirements and tasks come directly from the official Holberton project page .

🎯 Learning Objectives
By the end of this project, you should be able to explain, without using Google:

General Concepts
What RTFM means

What a shebang is

What the shell is

Difference between a terminal and a shell

What the shell prompt is

How to use command history

Navigation
What cd, pwd, ls do

How to navigate the filesystem

Meaning of . and ..

What the working directory is

What the root directory is

What the home directory is

Difference between /root and a user’s home directory

What hidden files are and how to list them

What cd - does

Looking Around
How to use ls, less, file

How to use options and arguments

How to read the long format of ls

A Guided Tour
What ln does

What symbolic and hard links are

Differences between them

Common Linux directories and their purpose

Manipulating Files
How to use cp, mv, rm, mkdir

What wildcards are and how they work

Working with Commands
What type, which, help, man do

Different kinds of commands

What an alias is

When to use help instead of man

Reading Man Pages
How to read a man page

What man page sections are

Section numbers for:

User commands

System calls

Library functions

Keyboard Shortcuts for Bash
Common Bash shortcuts

LTS
What LTS means

🛠️ Requirements
Allowed editors: vi, vim, emacs

Scripts tested on Ubuntu 22.04 LTS

Each script must be exactly 2 lines long

All files must end with a new line

First line of every script must be:

bash
#!/bin/bash
A README.md at the root of the repo describing the repository

A README.md inside this project folder describing each script

No use of backticks, &&, ||, or ;

All scripts must be executable (chmod u+x filename)

These requirements are listed on the project page .

🧩 Tasks Overview
This project includes 18 tasks, covering:

Printing the working directory

Listing files

Navigating directories

Displaying long formats

Showing hidden files

Creating and deleting directories

Creating symbolic and hard links

Moving and copying files

Cleaning Emacs backup files

Displaying directory trees

Example: Task 0 – Where am I?
Write a script that prints the absolute path of the current working directory.

Example from the project page :

Code
$ ./0-current_working_directory
/basics
$
📂 Project Structure
Code
holbertonschool-shell/
└── basics/
    ├── 0-current_working_directory
    ├── 1-listit
    ├── 2-bring_me_home
    ├── 3-listfiles
    ├── 4-listmorefiles
    ├── 5-listfilesdigitonly
    ├── 6-firstdirectory
    ├── 7-movethatfile
    ├── 8-firstdelete
    ├── 9-firstdirdeletion
    ├── 10-back
    ├── 11-lists
    ├── 12-file_type
    ├── 13-symbolic_link
    ├── 14-copy_html
    ├── 15-move
    ├── 16-clean_emacs
    └── 17-tree
✔️ Example Badge Set for GitHub
md
![Bash](https://img.shields.io/badge/Shell-Bash-blue)
![Linux](https://img.shields.io/badge/Linux-Ubuntu%2022.04-orange)
![Scripts](https://img.shields.io/badge/Scripts-2%20lines-lightgrey)
🎉 Conclusion
This project builds the foundation for all future DevOps and system‑level work.
By mastering shell basics, you gain the ability to navigate, inspect, and manipulate your system efficiently — a critical skill for any software engineer.
