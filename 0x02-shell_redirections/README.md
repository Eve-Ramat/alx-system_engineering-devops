**echo 'Hello, World'**
prints “Hello, World”, followed by a new line to the standard output.

**echo '"(Ôo)'\'**
displays a confused smiley "(Ôo)'
**echo 'Hello, World'**
prints “Hello, World”, followed by a new line to the standard output.

**echo '"(Ôo)'\'**
displays a confused smiley "(Ôo)'

**cat /etc/passwd**
displays the content of the /etc/passwd file

**cat /etc/passwd /etc/hosts**
display the content of /etc/passwd and /etc/hosts
**cat /etc/passwd**
Displays the content of the /etc/passwd file

**tail /etc/passwd**
displays the last 10 lines of /etc/passwd

**head /etc/passwd**
displays the first 10 lines of /etc/passwd

**head -n 3 iacta | tail -n 1**
displays the third line of the file iacta

**echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)**
a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

**ls -la > ls_cwd_content**
 a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it will be overwritten. If the file ls_cwd_content does not exist, it will be create it.

**tail -1 iacta >> iacta**
duplicates the last line of the file iacta.

**find . -type f -name "*.js" -delete**
a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

**find . -type d ! -path .  | wc -l**
a script that counts the number of directories and sub-directories in the current directory.

**ls -t .  | head**
a script that displays the 10 newest files in the current directory.

**egrep "root" /etc/passwd**
display lines containing the pattern “root” from the file /etc/passwd

**egrep -c "bin" /etc/passwd**
displays the number of lines that contain the pattern “bin” in the file /etc/passwd.

**egrep -A 3 "root" /etc/passwd**
Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

**egrep -A "bin" /etc/passwd**
display all the lines in the file /etc/passwd that do not contain the pattern “bin”.

**egrep ^[[:alpha:]] /etc/ssh/sshd_config**
displays all lines of the file /etc/ssh/sshd_config starting with a letter,  including capital letters as well.

**tr 'Ac' 'Ze'**
Replace all characters A and c from input to Z and e respectively.

**tr -d cC**
creates a script that removes all letters c and C from input.
