These are a series of tasks related to basic file and directory operations in a Unix-based environment. Each file represents a script or command that performs a specific operation on files or directories.

Here is a brief summary of each file and what it does:

File 0current_working_directory: Prints the current working directory.

File 1-listit: Displays the contents list of the current directory.

File 2-bring_me_home: Changes the working directory to the user's home directory.

File 3-listfiles: Displays current directory contents in a long format.

File 4-listmorefiles: Displays current directory contents, including hidden files (starting with ".").

File 5-listfilesdigitonly: Displays current directory contents in long format, with user and group IDs displayed numerically and hidden files.

File 6-firstdirectory: Creates a script that creates a directory named "my_first_directory" in the "/tmp/" directory.

File 7-movethatfile: Moves the file "betty" from "/tmp/" to "/tmp/my_first_directory".

File 8-firstdelete: Deletes the file "betty".

File 9-firstdirdeletion: Deletes the directory "my_first_directory" that is in the "/tmp" directory.

File 10-back: Writes a script that changes the working directory to the previous one.

File 11-lists: Writes a script that lists all files (including hidden files) in the current directory, the parent of the working directory, and the "/boot" directory, in long format.

File 12-file_type: Writes a script that prints the type of the file named "iamafile".

File 13-symbolic_link: Creates a symbolic link to "/bin/ls", named "ls".

File 14-copy_html: Creates a script that copies all HTML files from the current working directory to the parent of the working directory, but only copies files that did not exist in the parent directory or were newer than the versions in the parent directory.

File 100-lets_move: Creates a script that moves all files beginning with an uppercase letter to the directory "/tmp/u".

File 101-clean_emacs: Creates a script that deletes all files in the current working directory that end with the character "~".

File 102-tree: Creates a script that creates the directories "welcome/", "welcome/to/", and "welcome/to/school" in the current directory.'

File 103-commas: Writes a command that lists all the files and directories of the current directory, separated by commas (",").

File school.mgc: Creates a "magic" file that can be used with the "file" command to detect "School" data files, which always contain the string "SCHOOL" at offset 0.
