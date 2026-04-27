## Command: ssh
What it does: To connect to your Linux machine
Syntax: ssh username@IP_ADDRESS
Example: ssh username@98.126.117.9

## Command: ls
What it does: Lists all the files and directories in the current working directory
Syntax: ls [options]
Useful flags: -l (long format), -a (show hidden files)

## Command: pwd
What it does: Tells you your current directory/folder path
Syntax: pwd

## Command: cd
What it does: To change directory
Syntax: cd [path]
Example: cd / (root), cd .. (back one), cd (home)

## Command: touch
What it does: Create a new file
Syntax: touch [file_name]
Example: touch linode{1..10}, touch -d tomorrow file_name

## Command: echo
What it does: Prints text or adds content to a file
Syntax: echo [text]
Example: echo stuff > new_file.txt (adds "stuff" inside the file)

## Command: nano
What it does: Simple text editor
Syntax: nano [file_name]
Useful flags: To save: Ctrl + X, Y, Enter

## Command: vim
What it does: Advanced text editor for Linux pros
Syntax: vim [file_name]
Useful flags: To save: Esc then :wq

## Command: cat
What it does: See what is inside a file
Syntax: cat [file_name]

## Command: shred
What it does: Securely erases a file so it can't be recovered or seen
Syntax: shred [file_name]

## Command: mkdir
What it does: Create a new directory
Syntax: mkdir [directory_name]

## Command: cp
What it does: To copy a file
Syntax: cp [filename] [location]

## Command: mv
What it does: To move or rename a file
Syntax: mv [file_name] [location]

## Command: rm
What it does: To remove/delete a file
Syntax: rm [filename]

## Command: rmdir
What it does: Deletes/Removes an empty directory
Syntax: rmdir [directory_name]
Useful flags: rm -r (recursive; removes directory and everything inside)

## Command: ln
What it does: Creates a link for a file
Syntax: ln -s [file_name] [link_name]
Useful flags: -s (for soft link)

## Command: clear
What it does: Cleans/clears the terminal page
Syntax: clear

## Command: whoami
What it does: Shows which user account you are currently using
Syntax: whoami

## Command: useradd
What it does: To create a new username
Syntax: sudo useradd [name]

## Command: sudo
What it does: Execute a command with administrative (root) privileges
Syntax: sudo [command]

## Command: adduser
What it does: Adds a user and prompts to set a password
Syntax: sudo adduser [name]

## Command: su
What it does: Switch to another user account
Syntax: su [user_name]

## Command: exit
What it does: To exit from the current username or terminal session
Syntax: exit

## Command: passwd
What it does: Used to set or change a user password
Syntax: sudo passwd [user_name]

## Command: apt
What it does: Advanced Package Tool; the "app store" for Debian Linux
Syntax: sudo apt [options] [package]

## Command: finger
What it does: To inspect/view details of a user
Syntax: finger [user_name]

## Command: man
What it does: Shows the manual/documentation for a command
Syntax: man [something]

## Command: whatis
What it does: Briefly describes what a command or "something" is
Syntax: whatis [something]

## Command: which
What it does: Tells you the location of a specific command/executable
Syntax: which [something]

## Command: whereis
What it does: Tells you the location of all files related to a command
Syntax: whereis [something]

## Command: wget
What it does: To download files from the web
Syntax: wget [link]

## Command: curl
What it does: Transfers data from a URL
Syntax: curl [link] > [file_name]
