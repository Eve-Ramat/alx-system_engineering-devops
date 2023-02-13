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
