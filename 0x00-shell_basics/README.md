Scripts
pwd - script that prints the absolute path name of the current working directory.
ls- display the contents list of your current directory.
cd ~ - script that changes the working directory to the user’s home directory.
ls -l - display current directory contents in a long format.
ls -la - display current directory contents, including hidden files (starting with .). use the long format.
ls -na - display current directory contents.
mkdir /tmp/my_first_directory - script that creates a directory named my_first_directory in the /tmp/ directory.
mv /tmp/betty /tmp/my_first_directory - move the file betty from /tmp/ to /tmp/my_first_directory.
rm /tmp/my_first_directory/betty - delete the file betty.
rmdir /tmp/my_first_directory - delete the directory my_first_directory that is in the /tmp directory.
cd - -script that changes the working directory to the previous one.
ls -la . .. /boot – script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile – script that prints the type of the file named iamafile. the file iamafile will be in the /tmp directory when we will run your script.
ln -s /bin/ls ./__ls__ - create a symbolic link to /bin/ls, named __ls__. the symbolic link should be created in the current working directory.
cp -u ./*.html .. - script that copies all the html files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.


