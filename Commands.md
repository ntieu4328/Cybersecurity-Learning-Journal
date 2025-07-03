<h1>Commands</h1>

Kali Linux:
* echo - prints text
* whoami - shows current username
* ls - list files/directories
* cd - change directory
* cat - show file contents
* find - search for files
* grep - search for something in file
* & - run commands in background
* && - chain commands
* ">" - overwrite output
* ">>" - append output
* file - determines the type of file and its data
* exiftool - software used for reading, writing, and editing metadata
* cat etc/passwd - see what user's shell is set as
* lsb-release -a - shows what version of linux OS running
* nano (file name) - create and edit text files
* ./(.sh file) - run a .sh file
* git clone - download an existing Git repository
* cp (original file name) (new file name) - creates duplicate of file. Can be used to change file type (ex: .php -> .php5)
* curl http://(ip) > (desired file) - transfer data from a website to a desired file
* [RDP](https://github.com/ntieu4328/TryHackMe/blob/main/How%20to%20RDP%20Into%20Machine.md) - allows user to remotely access and control another computer over a network connection
* [SSH](https://github.com/ntieu4328/TryHackMe/blob/main/How%20to%20SSH%20Into%20Machine.md) - log onto remote systems on a command line interface

PowerShell:
* history found C:/Users/(user)/AppData/Roaming/Microsoft/Windows/PowerShell/PSReadLine/ConsoleHost_history
* Select-String - find string in file (PowerShell grep equivalent)
  * `Select-String -Path "(file path)" '(string)'`
 
Windows:
* windows + r -> lusrmgr.msc - edit and look at user accounts
* System32 folders - critical files for operating system
