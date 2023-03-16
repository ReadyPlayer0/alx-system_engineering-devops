

Here are a series of Bash scripts that perform various tasks related to file permissions and ownership. Here's a brief summary of each file's purpose:

File 0-iam_betty: Changes the current user to betty.

File 1-who_am_i: Prints the effective username of the current user.

File 2-groups: Prints all the groups the current user is a member of.

File 3-new_owner: Changes the owner of the file "hello" to betty.

File 4-empty: Creates an empty file called "hello".

File 5-execute: Adds execute permission for the owner to the file "hello".

File 6-multiple_permissions: Adds execute permission for the owner and group owner, and read permission for other users, to the file "hello".

File 7-everybody: Adds execute permission for the owner, group owner, and other users to the file "hello".

File 8-James_Bond: Sets the permissions for the file "hello" so that the owner, group owner, and other users all have all permissions.

File 9-John_Doe: Sets the permissions for the file "hello" to -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello.

File 10-mirror_permissions: Sets the permissions for the file "hello" to match those of "olleh".

File 11-directories_permissions: Adds execute permission for the owner, group owner, and other users to all subdirectories of the current directory, but not to regular files.

File 12-directory_permissions: Creates a directory called "my_dir" with permissions 751 in the working directory.

File 13-change_group: Changes the group owner of the file "hello" to "school".

File 100-change_owner_and_group: Changes the owner to "vincent" and the group owner to "staff" for all files and directories in the working directory.

File 101-symbolic_link_permissions: Changes the owner of the symbolic link "_hello" to "vincent" and the group owner to "staff".

File 102-if_only: Changes the owner of the file "hello" to "betty" only if it is currently owned by the user "guillaume".

File 103-Star_Wars: Plays the Star Wars Episode IV movie in the terminal.




