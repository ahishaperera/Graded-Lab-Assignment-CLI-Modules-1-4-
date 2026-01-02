### Command: uptime
This command displays the time elapsed since the system was last booted.

### Command: ps -u $USER
This command lists all processes currently running under my user account.

### Command: ps -u $USER -o pid,comm,%cpu --sort=-%cpu | head
This command identifies the process consuming the highest CPU usage among my running processes.

### Command: sleep 300 &    ,   jobs
The sleep command was started in the background, and jobs confirms it is running.

### Command: ps -u $USER          ,     renice 10 -p 353
The renice command changes the priority of a running process. A higher nice value means lower priority.

### Command : free -h
This command displays memory usage information in a readable format.

### Command : df -h ~
This command displays disk space usage for the filesystem containing my home directory.

### Command : echo $SHELL
This command displays the name of the shell currently in use.
