**Develop an elegantly coded program that successfully passes the Betty checks.
**Create a UNIX command line interpreter.
**Simple shell version 0.1 and above.

Ensure proper handling of the PATH variable.
Avoid calling the fork function if the command does not exist.
**Simple shell version 0.4 and above.

Incorporate the built-in "env" command to display the current environment.
**Simple shell version 0.1 and above.

Design and implement your own getline function.
Optimize reading operations by using a buffer to process multiple characters at once and minimize the use of the read system call.
Static variables should be utilized.
The getline function provided by the system is prohibited from use.

The program is not required to:

Enable cursor movement.
**Simple shell version 0.2 and above.


You are not allowed to use strtok
**Simple shell 0.4 +



handle arguments for the built-in exit

Usage: exit status, where status is an integer used to exit the shell
**Simple shell 1.0 +


Implement the built-in commands "setenv" and "unsetenv".

setenv:

Create a new environment variable or modify an existing one.
Command syntax: setenv VARIABLE VALUE.
In case of failure, an appropriate message should be printed on stderr.
unsetenv:

Remove an environment variable.
Command syntax: unsetenv VARIABLE.
In case of failure, an appropriate message should be printed on stderr.
Please ensure all documentation and communication are in English.