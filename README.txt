Title: Custom Shell Assignment
Author:Darren Mc Cole
Student Number: C13465962
Credit: TinyShell

tsh (tiny shell)
================

My custom shell is a changed version of tiny shell.
 
tsh is a tiny shell for Unix systems which is is written in Python.
It's use is to give users very restricted access to a system.

Implemented commands include:

ifc - ifconfig
pw - directory path

dt - the date command
ud - userid and group id commands

To implent this shell on another machine:

1. sudo bash to become root user
2. Create a user account with useradd <username>
3. Give user a password with passwd <username>
4. Ensure the file is cloned to your repository
5. Become the root user and grant permissions to the shell files
6. Point your shell to the directory you have stored the new shell in by
using: usermod -s /<file>/tsh <username>

  
