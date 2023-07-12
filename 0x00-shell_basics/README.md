# Scripts Description

This repository contains scripts for various purposes. Here is a brief description of each script:

- `0-current_working_directory`: This script prints the absolute path name of the current working directory.
- `1-listit`: This script displays the contents list of the current directory.
- `2-bring_me_home`: This script changes the working directory to the user's home directory, regardless of the current working directory.
- `3-listfiles`: This script prints the directory contents in long format.
- `4-listmorefiles`: This script prints the directory contents, (including hidden files) in the long format.
- `5-listfilesdigitonly1: This script prints the current directory contents, (including hidden files and user and gropu IDs displayed numerically) in long format.
- `6-firstdirectory`: This script creates a directory named `my_first_directory` in the `/tmp/` directory.
- `7-movethatfile`: This script moves the file betty from /tmp/ to /tmp/my_first_directory.
- `8-firstdelete`: This script deletes the file betty from the directory tmp/my_first_directory.
- `9-firstdirdeletion`: This script deletes the directory `my_first_directory` from `tmp`.
- `10-back`: This script changes the working directory to the previous one.
- `11-lists`: THis script list all files (including hidden ones) in the current directory and the parent of the working directory and the /boot directory in long format.
- `12-file_type`: This script prints the type of the file names iamafile that is in the /tmp directory.
- `13-symbolic_link`: This script creates a symbolic link to /bin/ls, named __ls__ in the current directory.
- `14-copy_html`: This script copies ann the HTML files from the current working directory to the parent of the working directory, but only copies only files that didn't exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
- `100-lets_move`: THis script moves all files begining woth an uppercase letter to the directory `/tmp/u`.
- `101-clean_emacs`: This script deletes all the files in the current working directory that ends with the character '~'
- `102-tree`: This script creates the directories 'welcome/, welcome/to/ and welcome/to/school' in the current directory.
- `103-commas`: This script lists all the files and directories of teh current directory, separated by commas (,). while ensuring that 
	Directory names end with a slash
	files and directories atarting with a dot are also listed
	The listing are alphabetically ordered, except for the directories . and .. which should be listed at the beginning
	Only digits and letters are used to sort; Digits coming first
	the listing should end with a new line
- `school.mgc`: This script creates a magic file `school.mgc` that can be used with the command file to dete4ct school data files.
