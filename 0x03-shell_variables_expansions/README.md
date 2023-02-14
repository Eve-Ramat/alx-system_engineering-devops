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

11. * echo "$(($BREATH ** $LOVE)): Displays the result of BREATH to the power LOVE. (BREATH and LOVE are environment variables)

12. * echo $((2#$BINARY)): Converts a number from base 2 to base 10. The number in base 2 is stored in the environment variable BINARY. The script displays the number in base 10, followed by a new line

13. * echo {a..z}{a..z} | tr " " "\n" | grep -v "oo": Creates a script that prints all possible combinations of two letters, except "oo"i.

14.  * printf "%02.2f\n" $NUM: Prints a number with two decimal places. The number will be stored in the environment variable NUM.

15.  * printf "%x\n" $DECIMAL: converts a number from base 10 to base 16. The number in base 10 is stored in the environment variable DECIMAL

16. * tr 'A-Za-z' 'N-ZA-Mn-za-m': Encodes and decodes text using the rot13 encryption.
