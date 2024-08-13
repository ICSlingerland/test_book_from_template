# Terminal Command line Cheat Sheet

Command line interface (CLI) is a text-based way to interact with a computer by typing commands, allowing users to manage files, configure systems, and run software efficiently.

## Nomenclature

Command line interface (CLI) $==$ Terminal $==$ Console $==$ Shell $==$  Prompt

Folder $==$ Directory
#### Location: folders and files

|  | Mac   | Windows      |
|--|----------|-------------|
|    Present Working Directory  | pwd      | pwd |
| List content of the present working directory | ls        |  ls   |
| Change: Change Directory | cd {directory} (`cd /path/to/directory`) | cd {directory} (`cd /path/to/directory`)  |
|   Touch: Creates a new file or updates the timestamp  | touch {filename} (`touch my_file.txt`) | touch {filename} (`touch my_file.txt`)|
| Create new directory  | mkdir {directory_name} (`mkdir my_folder`)  | mkdir {directory_name} (`mkdir my_folder`)   |
| Copy: Copies file or directory | cp {source} {target} (`cp my_file.txt my_folder`)| cp {source}  { target} (`cp my_file.txt my_folder`)|
| Moves a file or directory| mv {source} {target} (`mv my_file.txt my_folder`)| mv {source} {target} (`mv my_file.txt my_folder`)|
|Removes: Removes file |  rm {filename} (`rm my_file.txt`) |  rm {filename} (`rm my_file.txt`)|
|Removes: Removes directory|  rmdir {directory_name} (`rmdir my_folder`) |  rmdir {directory_name}  (`rmdir my_folder`) |



Open the **manual page** `man` for any of these commands to display the manual pages for a given command, providing detailed information on its usage, options, and features. 
`man pwd`
- navigation: - Use `j` to scroll down, `k` to scroll up, and `q` to quit and return to the Terminal.

To clean up your terminal `clear`
 
### Python
|  | Mac   | Windows      |
|--|----------|-------------|
|  Varifying and version  | `python3 --version` | `py -3 --version` |
| Opening Python shell | `python3`    |  `py3`   |
| run python files | python3 {py_file_name} `python3 filename.py` | py3 {py_file_name} `py3 filename.py`|
|Open python file in VS Code| code {py_file_name} `code filename.py` | code {py_file_name} `code filename.py` |

Add the code command for opening pythonfile in VS Code. Open pallete `Cmd +Shft + p`  (`<Shell Command: Install 'code' command in PATH> `)

 

### Environment

|  | Mac   | Windows      |
|--|----------|-------------|
|  creating virtual environment| `python3 -m venv env` | `python -m venv my_env` |
| activating virtual environment | `source my_env/bin/activate`    |  `my_env/\Scripts\/activate.bat or my_env\/Scripts\/activate`   |


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
