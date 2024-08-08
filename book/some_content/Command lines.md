
## Nomenclature

Command line interface (CLI) is a text-based way to interact with a computer by typing commands, allowing users to manage files, configure systems, and run software efficiently.


Command line interface (CLI) $==$ Terminal $==$ Console $==$ Shell $==$  Prompt
Folder $==$ Directory
#### Location: folders and files

|  | Mac   | Windows      |

|--|----------|-------------|

|    Present Working Directory  | pwd      | pwd |

| List content of the present working directory | ls        |  ls   |

| Change: Change Directory | cd [directory] ('cd /path/to/directory') | cd [dirctory] ('cd /path/to/directory')  |

|   Touch: Creates a new file or updates the timestamp  | touch [filename] ('touch my_file.txt') | touch [filename] ('touch my_file.txt')         |

| Create new directory  | mkdir {directory_name} ('mkdir my_folder')  | mkdir {directory_name} ('mkdir my_folder')   |

| Copy: Copies file or directory | cp {source} {target} ('cp my_file.txt my_folder')| cp {source}  { target} ('cp my_file.txt my_folder')|

| Moves a file or directory| mv {source} {target} ('mv my_file.txt my_folder')| mv {source} {target} ('mv my_file.txt my_folder')|

|Removes: Removes file |  rm {filename} ('rm my_file.txt') |  rm {filename} ('rm my_file.txt')|

|Removes: Removes directory|  rmdir {directory_name} ('rmdir my_folder') |  rmdir {directory_name}  ('rmdir my_folder') |






Open the **manual page** $man$ for any of these commands to display the manual pages for a given command, providing detailed information on its usage, options, and features. 
- man pwd
	- navigation: - Use `j` to scroll down, `k` to scroll up, and `q` to quit and return to the Terminal.

 clear $\hspace{5mm} \textit{Cleans up your terminal}$
 
### Python

varifying and version
	Windows: py -3 --version
	Mac/linux: python3 --version
	
Opening Python shell:
	Mac/linux: python3
	
	you can now type code in your shell terminal for example:
	 - print("Hello world") 
	 To quit your shell type: quite()

You can run python files:
- python3 filename.py


Add the code command for opening pythonfile in VS Code. Cmd +Shft + p, Shell Command: Install 'code' command in PATH

you can now 
 

### Virtual environment
creating
	Windows: python -m venv my_env
	Mac: python3 -m venv env

activating
	Windows: my_env/\Scripts\/activate.bat or my_env\/Scripts\/activate
	Mac: source my_env/bin/activate
	
deactivating
	deactivate

### Git

Check status:

	git status

Staging:

	git add [directory]
	git add [file]
	git add .   Stages new and changed files
	
	
Committing:

	git commit -m "[message]"
	
Pushing:

	git push

Pulling:

	git pull

Branches:


[github-cheat-sheet](https://github.com/0nn0/git-basics-cheatsheet)
[Mac-Ternminal-command-line-cheat-sheet](https://github.com/0nn0/terminal-mac-cheatsheet)
