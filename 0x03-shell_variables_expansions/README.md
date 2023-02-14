# Shell, init files, variables and expansions

1.  * alias ls="rm: Creates a script that creates an alias.(Name: ls, Value: rm *)

2.  * echo hello $USER: creates a script that prints hello user, where user is the current Linux

3.  * PATH=$PATH:/action: Adds /action to the PATH. /action should be the last directory the shell looks into when looking for a program.

4.  * echo $PATH | tr ':' '\n' | wc -l: Creates a script that counts the number of directories in the PATH.

5.  *printenv: Creates a script that lists environment variables.

6.  *set: create a script that lists all local variables and environment variables, and functions.

7.  * BEST=School
:creates a new local variable.(Name: BETTY, Value: Holberton)

8.  * export BEST=School: create a script that creates a new global variable.(Name: HOLBERTON, Value: Betty)

9.  * echo $((128 + $TRUEKNOWLEDGE)): Prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
