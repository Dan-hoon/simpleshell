# simpleshell

This simple shell is a C program that I built for my homework of CSC 222, System Programing course at Louisiana Tech in Winter 2021-2022. It supports shell commands with I/O re-direction. 
Once, a user enters a command string (ended with a return key), this program parse the command and
handle I/O redirection signified by > for output to a file or < for input from a file.
The program has also 3 built-in commands that cd, pwd, and exit. The built-in functions are not executed 
by forking and executing an executable. Instead, the shell process executes them itself. All other commands are executed in a child process.

