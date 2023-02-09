pwd: a script that prints the absolute path name of the current working directory.

ls: displays the contents list of your current directory.

cd: a script that changes the working directory to the user’s home directory.

ls -l: displays current directory contents in a long format.

ls -la: displays current directory contents, including hidden files in a long format.

ls -la --numeric-uid-gid: displays all files, including hidden files, in a long format with their user and group IDs displayed numerically.

mkdir /tmp/my-first-directory: creates the /my-first-directory directory in the /tmp/ directory. Note: substitute the hyphens with underscores.
mv /tmp/betty /tmp my-first-director/betty: moves the file betty from /tmp/ to /tmp/my-first-directory.

rm /tmp/my-first-directory/betty: deletes the file betty from /tmp/my-first-directory.

rm -r /tmp/my-first-directory: deletes a directory named "my-first-directory" that is located in the "/tmp" directory.

cd - : changes the working directory to the previous one.


ls -la . .. /boot : a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

file /tmp/iamafile -  a script that prints the type of the file named iamafile.

ln -s /bin/ls __ls__ 
Creates a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
