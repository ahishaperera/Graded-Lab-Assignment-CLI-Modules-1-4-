### Command: uptime
This command displays the time elapsed since the system was last booted.

### Command: ps -u $USER
This command lists all processes currently running under my user account.

### Command: ps -u $USER -o pid,comm,%cpu --sort=-%cpu | head
This command identifies the process consuming the highest CPU usage among my running processes.
