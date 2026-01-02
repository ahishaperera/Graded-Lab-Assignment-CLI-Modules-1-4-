### Command: echo "This is some sample data for testing links" > ~/sample_data.txt
This command creates a file named sample_data.txt in my home directory and writes sample text into it.

### Command: ln ~/sample_data.txt ~/sample_hard.txt
This command creates a hard link named sample_hard.txt pointing to the same inode as sample_data.txt.
Hard links are additional names for the same file content.

### Command: ln -s ~/sample_data.txt ~/sample_soft.txt
This command creates a symbolic (soft) link named sample_soft.txt that points to sample_data.txt.
Unlike a hard link, a symbolic link has its own inode.

