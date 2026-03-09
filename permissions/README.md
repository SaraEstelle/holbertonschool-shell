Shell, Permissions
Holberton School – System Engineering & DevOps

📘 Overview
This project introduces Linux permissions, user and group management, and privilege escalation.
It is the second project in the Shell track and teaches you how to control access to files, switch users, modify ownership, and understand the permission model used by Unix systems.

All requirements and tasks come directly from the official Holberton project page  .

🎯 Learning Objectives
By the end of this project, you should be able to explain, without using Google:

Permissions
What chmod, sudo, su, chown, chgrp do

How Linux file permissions work

How to represent permissions (owner, group, other) as a single digit

How to change permissions, owner, and group of a file

Why a normal user cannot chown a file

How to run commands with root privileges

How to switch user ID or become superuser

User & Group Management
How to create a user

How to create a group

How to print real and effective user IDs

How to print the groups a user belongs to

How to print the effective user ID

📚 Resources
Recommended reading:

Permissions

man chmod

man sudo

man su

man chown

man chgrp

man id

man groups

man whoami

man adduser

man useradd

man addgroup

🛠️ Requirements
Allowed editors: vi, vim, emacs

Scripts tested on Ubuntu 22.04 LTS

Each script must be exactly 2 lines long

All files must end with a new line

First line of every script must be:

bash
#!/bin/bash
A README.md describing each script is required

No use of backticks, &&, ||, or ;

All scripts must be executable

Some tasks must be done inside the sandbox (tasks 3, 13, 14, 15, 16)  

🧩 Tasks Overview
This project includes 17 tasks, covering:

Switching users

Printing user identity

Listing groups

Changing file ownership

Creating empty files

Adding execute permissions

Setting specific permission modes

Creating directories with permissions

Changing group ownership

Modifying symbolic links

Applying permissions recursively

Example: Task 0 – My name is Betty
Create a script that switches the current user to betty.

Must use exactly 8 characters (plus newline)

Assumes the user betty exists

Example from the project page  :

Code
$ tail -1 0-iam_betty | wc -c
9
📂 Project Structure
Code
holbertonschool-shell/
└── permissions/
    ├── 0-iam_betty
    ├── 1-who_am_i
    ├── 2-groups
    ├── 3-new_owner
    ├── 4-empty
    ├── 5-execute
    ├── 6-multiple_permissions
    ├── 7-everybody
    ├── 8-James_Bond
    ├── 9-John_Doe
    ├── 10-mirror_permissions
    ├── 11-directories_permissions
    ├── 12-directory_permissions
    ├── 13-change_group
    ├── 14-owner_and_group
    ├── 15-symbolic_link_permissions
    └── 16-if_only
✔️ Example Badge Set for GitHub
md
![Permissions](https://img.shields.io/badge/Linux-Permissions-green)
![Users](https://img.shields.io/badge/Users-Groups-blue)
![Root](https://img.shields.io/badge/Privilege-Root-red)
🎉 Conclusion
This project builds the foundation for understanding Linux security, user management, and file access control.
Mastering permissions is essential for DevOps, system administration, and secure software development.
