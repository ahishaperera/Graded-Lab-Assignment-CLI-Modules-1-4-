### Command: whoami
This command displays the username of the currently logged in user.It confirms that I am operating the system using my own login account.
### Command: groups
This command lists all the groups that my user account belongs to. It helps verify my access permissions on the system.

### Command: pwd
This command prints the present working directory. It confirms the exact location where I am working.
### Command: ls -l
This command lists all files and directories in the current directory in long format, showing permissions, ownership, size and modification time.

### Command: echo "Linux user environment verified" > user_info.txt
This command creates a file named user_info.txt and writes the specified line into it, confirming that the user environment has been verified.

### Command: wc -c user_info.txt
This command counts the number of characters present in the file user_info.txt, helping verify the file’s content integrity.

### Command: man mkdir
This command opens the manual page for the mkdir command, providing detailed documentation about its usage and options.
### Useful Option: -p
The -p option allows creation of parent directories if they do not already exist, preventing errors when creating nested directories.

### Command: ls ~ | sort
This command lists the contents of my home directory in alphabetical order. 
At this point, only the file user_info.txt exists because this is a new terminal session.

### Command: grep "admin" log.txt
This command searches for the word "admin" inside log.txt and displays only the lines that contain matching text.

### Command: uname -r
This command displays the currently running Linux kernel version, providing system-level information.

### Command: ping -c 4 www.google.com
This command sends ICMP packets to Google’s server to verify network connectivity. Successful replies confirm internet access.
