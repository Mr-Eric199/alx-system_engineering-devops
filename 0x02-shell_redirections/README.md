0.	echo “hello, world” - script that prints “hello, world”, followed by a new line to the standard output.
1.	echo "(ôo)'" - a script that displays a confused smiley "(ôo)'
2.	cat /etc/passwd - display the content of the /etc/passwd file.
3.	cat /etc/passwd /etc/hosts - display the content of /etc/passwd and /etc/hosts
4.	tail -n 10 /etc/passwd - display the last 10 lines of /etc/passwd
5.	head -n 10 /etc/passwd - display the first 10 lines of /etc/passwd
6.	head -n 3 iacta | tail -n 1 - script that displays the third line of the file iacta.
7.	 echo "best school" > '*\\\'"best school"\''\\*$?******:)' - script that creates a file named exactly \*\\'"best school"\'\\*$\?\*\*\*\*\*:) containing the text best school ending by a new line.
8.	ls -la > ls_cwd_content - script that writes into the file ls_cwd_content the result of the command ls -la. if the file ls_cwd_content already exists, it should be overwritten. if the file ls_cwd_content does not exist, create it.
9.	tail -n 1 iacta >> iacta - script that duplicates the last line of the file iacta
10.	find . -type f -name "*.js" -delete - script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
11.	find . -mindepth 1 -type d | wc -l - script that counts the number of directories and sub-directories in the current directory.
12.	ls -lt | head -n 10 - script that displays the 10 newest files in the current directory.
13.	 sort | uniq -u | awk 'nf==1' - script that takes a list of words as input and prints only words that appear exactly once.
14.	grep "root" /etc/passwd - display lines containing the pattern “root” from the file /etc/passwd
15.	grep -c "bin" /etc/passwd - display the number of lines that contain the pattern “bin” in the file /etc/passwd
16.	grep -a 3 "root" /etc/passwd - display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
17.	grep -v "bin" /etc/passwd - display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
18.	grep "^[[:alpha:]]" /etc/ssh/sshd_config - display all lines of the file /etc/ssh/sshd_config starting with a letter.
19.	tr 'ac' 'ze' - replace all characters a and c from input to z and e respectively.
20.	tr -d 'cc' - script that removes all letters c and c from input.
21.	rev - script that reverse its input.
22.	awk -f: '{print "user:", $1, "\thome directory:", $6}' /etc/passwd | sort - script that displays all users and their home directories, sorted by users.

