## Shell Basics ##

**0. Where Am I?**

0-current_working_directory prints the absolute path name of the current working directory.

**1. What’s in there?**

1-listit displays the contents for the current directory as a list.

**2. There is no place like home**

2-bring_me_home changes the working directory to the user’s home directory.

**3. The long format**

3-listfiles displays the contents of the current directory in a long format.

**4. Hidden files**

4-listmorefiles displays the current directory's contents, including hidden files (starting with .). Using the long format.

**5. I love numbers**

5-listfilesdigitonly displays current directory contents in:
	- long format
	- with user and group IDs displayed numerically
	- with hidden files starting with (.)

**6. Welcome**

6-firstdirectory creates a directory named *my_first_directory* in the */tmp/* directory.

**7. Betty in my first directory**

7-movethatfile moves the file betty from */tmp/* to */tmp/my_first_directory*.

**8. Bye bye Betty**

8-firstdelete deletes the file betty from */tmp/my_first_directory*.

**9. Bye bye My first directory**

9-firstdirdeletion deletes *my_first_directory* from the */tmp* directory.

**10. Back to the future**

10-back changes the working directory to the previous one.

**11. Lists**

11-lists lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

**12. File type**

12-file_type prints the type of the file named *iamafile* in the */tmp/* directory.

**13. We are symbols, and inhabit symbols**

13-symbolic_link creates a a symbolic link in the current directory to */bin/ls*, named __ls__.

**14. Copy HTML files**

14-copy_html copies all the HTML files from the current working directory to the parent of the working directory, but only copies files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

**15. Let’s move**

100-lets_move moves all files beginning with an uppercase letter to the directory */tmp/u*.

**16. Clean Emacs**

101-clean_emacs deletes all files in the current working directory that end with the character ~.

**17. Tree**

102-tree creates the directories *welcome/*, *welcome/to/* and *welcome/to/school* in the current directory.

**18. Life is a series of commas, not periods**

103-commas lists all the files and directories of the current directory, separated by commas (,).
	- Directory names should end with a slash (/)
	- Files and directories starting with a dot (.) should be listed
	- The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
	- Only digits and letters are used to sort; Digits should come first

**19. File type: School**

A magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
