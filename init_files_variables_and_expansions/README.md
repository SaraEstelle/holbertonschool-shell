Shell, Init Files, Variables and Expansions
Holberton School – System Engineering & DevOps

https://img.shields.io/badge/Progress-100%25-brightgreen  
https://img.shields.io/badge/Shell-Bash-blue  
https://img.shields.io/badge/Level-Amateur-yellow  
https://img.shields.io/badge/Ubuntu-20.04-orange

📘 Overview
This project dives into shell initialization, environment variables, expansions, arithmetic, and aliases.
It teaches how the shell starts, how variables behave, how commands are expanded, and how to customize your environment.

It is a key step in understanding how Bash works under the hood and how to control your shell environment effectively.

(Reference: )

🎯 Learning Objectives
By the end of this project, you should be able to explain, without using Google:

General
What happens when you type:

Code
ls -l *.txt
Shell Initialization Files
What /etc/profile is

What /etc/profile.d/ contains

What ~/.bashrc does

Variables
Difference between local and global variables

What a reserved variable is

How to create, update, and delete shell variables

Roles of reserved variables:

HOME

PATH

PS1

What special parameters are

What $? represents

Expansions
What expansions are and how they work

Difference between single and double quotes

How to perform command substitution using:

$( )

backticks `

Shell Arithmetic
How to perform arithmetic operations in Bash

Aliases
How to create an alias

How to list aliases

How to temporarily disable an alias

Other Concepts
How to execute commands from a file in the current shell (source or .)

(Reference: )

📚 Resources
Recommended reading:

Expansions

Shell Arithmetic

Variables

Shell initialization files

The alias command

man printenv

man set

man unset

man export

man alias

man unalias

man source

man printf

🛠️ Requirements
Allowed editors: vi, vim, emacs

Scripts tested on Ubuntu 20.04 LTS

Each script must be exactly 2 lines long

All files must end with a new line

First line of every script must be:

bash
#!/bin/bash
A README.md describing each script is required

No use of &&, ||, or ;

No use of bc, sed, or awk

All scripts must be executable

(Reference: )

🧩 Tasks Overview
This project includes 18 tasks, covering:

Printing variables

Creating local and global variables

Performing arithmetic

Using expansions

Creating aliases

Converting numbers

Understanding shell startup behavior

Writing a technical blog post (advanced task)

Example: Task 15 – What happens when you type ls *.c
You must write a professional blog post explaining step‑by‑step what happens inside the shell when executing this command.

Requirements include:

At least one image

Published on Medium or LinkedIn

Written in English

Shared publicly

Added to the project for manual review

(Reference: )

📂 Project Structure
Code
holbertonschool-shell/
└── init_files_variables_and_expansions/
    ├── 0-alias
    ├── 1-hello_you
    ├── 2-path
    ├── 3-paths
    ├── 4-global_variables
    ├── 5-local_variables
    ├── 6-create_local_variable
    ├── 7-create_global_variable
    ├── 8-true_knowledge
    ├── 9-divide_and_rule
    ├── 10-love_exponent_breath
    ├── 11-binary_to_decimal
    ├── 12-combinations
    ├── 13-print_float
    ├── 14-decimal_to_hexadecimal
    ├── 15-what_happens_when_ls_c (blog post)
    ├── 16-encryption
    ├── 17-odd
    └── 18-water_and_stir
✔️ Example Badge Set for GitHub
md
![Variables](https://img.shields.io/badge/Shell-Variables-blue)
![Expansions](https://img.shields.io/badge/Bash-Expansions-green)
![Aliases](https://img.shields.io/badge/Customization-Aliases-yellow)
🎉 Conclusion
This project deepens your understanding of how the shell works internally — from initialization to variable handling, expansions, arithmetic, and aliases.
Mastering these concepts gives you the power to customize your environment, write more advanced scripts, and understand the behavior of Bash at a deeper level.
