# Shell Permissions

In this project, I learned about permissions, how the commands chown, chgrp, chmod, sudo, and 
su are used to navigate, create and manipulate permissions access. I also learned what the read, 
write and execute permissions are, how to represent each of the three sets of permissions (owner,
group, and other) as a single digit, and how to change permissions, owner and group of a file.

## Tasks :page_with_curl:

* **0. My name is Betty**
  * [0-iambetty](./0-iambetty): Create a script that switches the current user to the user betty.
  * You should use exactly 8 characters for your command (+1 character for the new line)
  * You can assume that the user betty will exist when we run your script

* **1. Who am I?**
  * [1-whoami](./1-whoami): Write a script that prints the effective username of the current user.
 
 * **2. Groups**
  * [2-groups](./2-groups): Write a script that prints all the groups the current user is part of.
 
 * **3. New owner**
  * [3-new_owner](./3-new_owner): Write a script that changes the owner of the file hello to the user betty.

* **4. Empty!**
  * [4-empty](./4-empty): Write a script that creates an empty file hello

* **5. Execute**
  * [5-execute](./5-execute): Write a script that adds execute permission to the owner of the file hello.
  * The file hello will be in the working directory

* **6. Multiple permissions**
  * [6-multiple_permisssions](./6-multiple_permissions): Write a script that adds execute permission to the owner 
 and the group owner, and read permission to other users, to the file hello.
  * The file hello will be in the working directory

* **7. Everybody!**
  * [7-everybody](./7-everybody): Write a script that adds execution permission to the owner, the group owner and the 
 other users, to the file hello
  * The file hello will be in the working directory
  * You are not allowed to use commas for this script

* **8. James Bond**
  * [8-James_Bond](./8-James_Bond): Write a script that sets the permission to the file hello as follows:
  * Owner: no permission at all
  * Group: no permission at all
  * Other users: all the permissions
  * The file hello will be in the working directory You are not allowed to use commas for this script

* **9. John Doe**
  * [9-John_Doe](./9-John_Doe): Write a script that sets the mode of the file hello to this:
 -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
  * The file hello will be in the working directory
  * You are not allowed to use commas for this script

* **10. Look in the mirror**
  * [10-mirror_permissions](./10-mirror-permissions): Write a script that sets the mode of the file hello 
the same as olleh’s mode.
  * The file hello will be in the working directory
  * The file olleh will be in the working directory

* **11. Directories**
  * [11-directories_permissions](./11-directories_permissions): Create a script that adds execute permission 
to all subdirectories of the current directory for the owner, the group owner and all other users.
  * Regular files should not be changed.

* **12. More directories**
  * [12-more_directory](./12-more_directory): Create a script that creates a directory called my_dir with permissions 
751 in the working directory.

* **13.Change group**
  * [13-change_group](./13-change_group): Write a script that changes the group owner to school for the file hello
  * The file hello will be in the working directory
 
* **14. Owner and group**
  * [100-change_owner_and_group](./100-change_owner_and_group): Write a script that changes the owner to vincent and the
 group owner to staff for all the files and directories in the working directory.
 
* **15. Symbolic links**
  * [101-symbolic_link_permissions](./101-symbolic_link_permissions): Write a script that changes the owner and the group
owner of _hello to vincent and staff respectively.
  * The file _hello is in the working directory
  * The file _hello is a symbolic link

* **16. If only**
  * [102-if_only](./102-if_only): Write a script that changes the owner of the file hello to betty only if it is owned by
the user guillaume.
  * The file hello will be in the working directory

* **17. Star Wars**
  * [103-star_wars](./103-star_wars): Write a script that will play the StarWars IV episode in the terminal.
