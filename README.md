# hello-world-bash

## Useful commands

Time and Date:
- cal
- date
- wich date
- cd /usr/bin
- ls -l ( all different commands )

Disk Usage or File Size: 
- df -h
- du -sh *

System Performance
- top

# Using the shell
Exploring
- pwd
- ls -lah ( shows list of unix permissions, size of files )
- cd /tmp cd ~
- which python3

Use python in terminal
python3
import os
print(os.getcwd())
exit()

Viewing files
- less /etc/passwd
- cat /etc/passwd

Counting lines
- wc -l /etc/passwd

# Modifying Files And Directories
- touch newfile.txt
- mkdir newdir
- mv filename.xx newdir/
- cat newdir/filename.xx ( print content )
- mkdir -p moredir/dir1/dir2 ( create multiple directorys )
- rm rf moredir ( delete directory )

# Processes
- ps
- ./sleeper.sh & ( stop with ctrl + z )
- fg 1

# Shell piping
List all files in directory and count num files and write to outputfile
- ls -l usr/bin | wc -l > output.txt

Set a variable
- STR=$'1. This is a line\n2. This is a line\n3. This is a line.'

Print it and write to file
- echo "$STR" > lines.txt

Write out the content of the file and sort in reverse add less to be able to go up/down inthe file
- cat lines.txt | sort -r | less

Search for a specific char
- cat lines.txt | grep 3 

Append to file
- echo "something" > append.txt
- echo "something else" >> append.txt