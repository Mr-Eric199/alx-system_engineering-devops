su betty - create a script that switches the current user to the user betty.
whoami - script that prints the effective username of the current user.
groups - prints all the groups the current user is part of.
chown betty hello -script that changes the owner of the file hello to the user betty.
touch hello - creates an empty file called hello.
chmod u+x hello -adds execute permission to the owner of the file hello
chmod ug+x,o+r hello - adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod ugo+x -adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007 hello - sets the permission to the file hello as follows:
•	owner: no permission at all
•	group: no permission at all
•	other users: all the permissions
chmod 753 hello -sets the mode of the file hello to this:
-rwxr-x-wx 1 julien julien 23 sep 20 14:25 hello

chmod --reference=olleh hello -sets the mode of the file hello the same as olleh’s mode
chmod  -r ugo+x -adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. regular files should not be changed
mkdir -m 751 my_dir - script that creates a directory called my_dir with permissions 751 in the working directory.
chgrp school hello - script that changes the group owner to school for the file hello



