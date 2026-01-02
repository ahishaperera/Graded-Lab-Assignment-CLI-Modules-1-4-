### Command: echo "This is some sample data for testing links" > ~/sample_data.txt
This command creates a file named sample_data.txt in my home directory and writes sample text into it.

### Command: ln ~/sample_data.txt ~/sample_hard.txt
This command creates a hard link named sample_hard.txt pointing to the same inode as sample_data.txt.
Hard links are additional names for the same file content.

### Command: ln -s ~/sample_data.txt ~/sample_soft.txt
This command creates a symbolic (soft) link named sample_soft.txt that points to sample_data.txt.
Unlike a hard link, a symbolic link has its own inode.

### Command: ls -i sample_data.txt sample_hard.txt sample_soft.txt
This command displays the inode numbers of the three files.
Files with the same inode share the same data on disk.
### Analysis:
sample_data.txt and sample_hard.txt share the same inode because hard links point to the same underlying file.
sample_soft.txt has a different inode because symbolic links are separate files pointing to the target.

### Command: ls -l sample_data.txt
Displays file permissions, ownership, size, and modification time.

### Command: stat sample_data.txt
Displays detailed file metadata including access, modify, change timestamps, and inode number.
