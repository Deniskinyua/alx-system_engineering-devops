## 0X00. SHELL, BASICS

0. Task 0: Where am I?
   
> Write a script that prints the absolute path name of the current working directory.
>> 0-current_working_directory
1. Task 1: What's in there?
> Display the contents list of your current directory.
>> 1-listit
2. Task 2: There is no place like home
> Write a script that changes the working directory to the user’s home directory (You are not allowed to use any shell variables)
>> 2-bring_me_home
3. Task 3: The long format
> Display current directory contents in a long format
>> 3-listfiles
4. Task 4: Hidden Files
> Display current directory contents, including hidden files (starting with .). Use the long format.
>> 4-listmorefiles
5. Task 5: I Love Numbers
> Display current directory contents.
- long format, with user and group IDs displayed numerically, And hidden files (starting with .)
>> 5-listfilesdigitonly
6. Welcome
> Create a script that creates a directory named my_first_directory in the /tmp/ directory.
>> 6-firstdirectory
7. Betty in My First Directory
> Move the file betty from /tmp/ to /tmp/my_first_directory.
>> 7-movethatfile
8. Bye Bye Betty
> Delete the file betty (The file betty is in /tmp/my_first_directory)
>> 8-firstdelete
9. Bye Bye My First Directory
> Delete the directory my_first_directory that is in the /tmp directory.
>> 9-firstdirdeletion
10. Back to the Future
> Write a script that changes the working directory to the previous one.
>> File: 10-back
11. Lists
> Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
>> 11-lists
12. File Type
> Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
>> 12-file_type
13. We are Symboles, and Inhabit Symbols
> Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
>> 13-symbolic_link
14. Copy HTML Files
>Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.You can consider that all HTML files have the extension .html
>> 14-copy_html
15. Let's Move
> Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.

You can assume that the directory /tmp/u will exist when we will run your script
>> 100-lets_move
16. Clean Emacs
> Create a script that deletes all files in the current working directory that end with the character ~.
>> 101-clean_emacs
17. Tree
> Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

You are only allowed to use two spaces (and lines) in your script, not more.
>> 102-tree
18. Life is Series of Commas, not Periods
> Write a command that lists all the files and directories of the current directory, separated by commas (,).

- Directory names should end with a slash (/)
- Files and directories starting with a dot (.) should be listed
- The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
- Only digits and letters are used to sort; Digits should come first
- You can assume that all the files we will test with will have at least one letter or one digit
- The listing should end with a new line
> 103-commas
19. File Type: Symbol
> Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
>> school.mgc
