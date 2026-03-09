Shell, I/O Redirections and Filters
Holberton School – System Engineering & DevOps

📘 Overview
This project introduces I/O redirections, filters, and special characters in the Unix shell.
It teaches how to manipulate input and output streams, chain commands, filter text, and work with essential command‑line tools.

This is one of the most important foundational projects in the Shell track, as it builds the skills needed for scripting, automation, and DevOps workflows.

(Reference: )

🎯 Learning Objectives
By the end of this project, you should be able to explain, without using Google:

Shell I/O Redirection
What head, tail, find, wc, sort, uniq, grep, tr do

How to redirect standard output to a file (>, >>)

How to read standard input from a file (<)

How to pipe output from one program to another (|)

How to combine commands and filters

Special Characters
White spaces

Single quotes '

Double quotes "

Backslash \

Comments #

Pipes |

Command separators

Tilde ~

Other Key Concepts
How to display text (echo)

How to concatenate files (cat)

How to reverse strings (rev)

How to cut sections from lines (cut)

What /etc/passwd and /etc/shadow contain and their formats

(Reference: )

📚 Resources
Recommended reading:

Shell, I/O Redirection

Special Characters

man echo

man cat

man head

man tail

man find

man wc

man sort

man uniq

man grep

man tr

man rev

man cut

man 5 passwd

🛠️ Requirements
Allowed editors: vi, vim, emacs

Scripts tested on Ubuntu 20.04 LTS

Each script must be exactly 2 lines long

All files must end with a new line

First line of every script must be:

bash
#!/bin/bash
A README.md describing each script is required

No use of backticks, &&, ||, or ;

All scripts must be executable

You are not allowed to use sed or awk

(Reference: )

🧩 Tasks Overview
This project includes 27 tasks, covering:

Displaying text

Reading files

Redirecting input/output

Filtering text

Sorting and counting

Removing patterns

Reversing strings

Extracting fields

Working with /etc/passwd

Finding files

Advanced filtering and command combinations

Example: Task 23 – Empty casks make the most noise
Write a command that finds all empty files and directories in the current directory and subdirectories.

Requirements:

Display only names (not paths)

Include hidden files

One name per line

No basename, grep, egrep, fgrep, or rgrep

Example output from the project page:

Code
Rona_napping.gif
javascript
root.gif
..something
Kris_is_awesome :)
..hello.gif
file.sh
docker.gif
README.md
index.html
main.gif
cat.gif
rudy_rigot.gif
.horrible_selfie.gif
........gif
📂 Project Structure
Code
holbertonschool-shell/
└── io_redirections_and_filters/
    ├── 0-hello_world
    ├── 1-confused_smiley
    ├── 2-hellofile
    ├── 3-twofiles
    ├── 4-lastlines
    ├── 5-firstlines
    ├── 6-third_line
    ├── 7-file
    ├── 8-cwd_state
    ├── 9-duplicate_last_line
    ├── 10-no_more_js
    ├── 11-directories
    ├── 12-newest_files
    ├── 13-unique
    ├── 14-findthatword
    ├── 15-countthatword
    ├── 16-whatsnext
    ├── 17-hidethisword
    ├── 18-letteronly
    ├── 19-AZ
    ├── 20-hiago
    ├── 21-reverse
    ├── 22-users_and_homes
    ├── 23-empty_casks
    ├── 24-gifs
    ├── 25-acrostic
    └── 26-the_biggest_fan
✔️ Example Badge Set for GitHub
md
![Redirections](https://img.shields.io/badge/Shell-I%2FO%20Redirections-blue)
![Filters](https://img.shields.io/badge/Text-Filters-green)
![Pipes](https://img.shields.io/badge/Commands-Pipes%20%7C%20Filters-yellow)
🎉 Conclusion
This project strengthens your understanding of text processing, command chaining, and I/O manipulation — essential skills for DevOps, scripting, and automation.
Mastering these tools gives you the power to process data efficiently and build more advanced shell scripts.
