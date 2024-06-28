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