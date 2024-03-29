# Shell, basics

In this project, I learned what the shell was and used basic shell commands like
pwd, ls, cd, mkdir, less, ln, rm, cp, and mv. I also practiced working with the 
'type', 'which' and 'help', 'man' and 'file' commands, I also learned how to use
wildcards, create html links, symbolic links, and magic files.

## Tasks :page_with_curl:

* **0. Where am I?**
  * [0-current_working_directory](./0-current_working_directory): Bash script that
  prints the absolute pathname of the current working directory.
  
* **1. What's in there?**
  * [1-listit](./1-listit): Bash script that displays the contents list of current directory.

* **2. There's no place like home**
  * [2-bring_me_home](./2-bring_me_home): Bash script that changes the working directory to the
  user's home directory.
  
* **3. The long format**
  * [3-listfiles](./3-listfiles): Bash script that displays current directory contents in
  long format.
  
* **4. Hidden files**
  * [4-listmorefiles](./4-listmorefiles): Bash script that displays current directory contents,
  including hidden files, using long format.
  
* **5. I love numbers**
  * [5-listfilesdigitonly](./5-listfilesdigitonly): Bash script that displays current directory
  contents, including hidden files, as follows:
    * Long format.
    * User and group ID's displayed numerically.

* **6. Welcome**
  * [6-firstdirectory](./6-firstdirectory): Bash script that creates a directory named `holberton`
  in the `/tmp/` directory.
  
* **7. Betty in my first directory**
  * [7-movethatfile](./7-movethatfile): Bash script that moves the file `betty` from `/tmp/` to
  `/tmp/holberton`.
  
* **8. Bye bye Betty**
  * [8-firstdelete](./8-firstdelete): Bash script that deletes the file `betty` in `/tmp/holberton`.
 
* **9. Bye bye My first directory**
  * [9-firstdirdeletion](./9-firstdirdeletion): Bash script that deletes the directory `holberton`
  in the `/tmp` directory.
  
* **10. Back to the future**
  * [10-back](./10-back): Bash script that changes the working directory to the previous one.
  
* **11. Lists**
  * [11-lists](./11-lists): Bash script that lists all files, including hidden files, in the
  current directory, parent of the working directory, and `/boot` directory, using long format.
  
* **12. File type**
  *  [12-file_type](./12-file_type): Bash script that prints the type of the file named
  `iamafile` located in the `/tmp` directory.
  
* **13. We are symbols and inhabit symbols**
  * [13-symbolic_link](./13-symbolic_link): Bash script that creates a symbolic link to `/bin/ls`,
  named `__ls__`.
  
* **14. Copy HTML files**
  * [14-copy_html](./14-copy_html): Bash script that copies all HTML files from the current
  working directory to the parent of the working directory, but only those that
  did not exist in the parent directory or were newer than the versions in the parent working directory.

* **15. Let's move**
  * [100-lets_move](./100-lets_move): Bash script that moves all files beginning with an uppercase
  letter to the directory `/tmp/u`.
  
* **16. Clean EMACS**
  * [101-clean_emacs](./101-clean_emacs): Create a script that deletes all files in the current working
  directory that end with the character ~.
 
* **17. Tree**
  * [102-tree](./102-tree): Create a script that creates the directories welcome/, welcome/to/ and 
  welcome/to/school in the current directory.
  * You are only allowed to use two spaces (and lines) in your script, not more.
 
* **18. Life is a series of commas, not periods**
  * [103-commas](./103-commas): Write a command that lists all the files and directories of the current 
  directory, separated by commas (,).
  * Directory names should end with a slash (/)
  * Files and directories starting with a dot (.) should be listed
  * The listing should be alpha ordered, except for the directories . and .. which should be listed at the
  very beginning
  * Only digits and letters are used to sort; Digits should come first
  * You can assume that all the files we will test with will have at least one letter or one digit
  * The listing should end with a new line
 
* **19. File type: School**
  * [school.mgc](./school.mgc): Create a magic file school.mgc that can be used with the command file to detect 
  School data files. School data files always contain the string SCHOOL at offset 0.
