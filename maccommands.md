Mac Commands
============
 **. refers to the current directory** <br>
 **.. refers to the parent directory of current directory**
 
_A list of my commonly used  Mac commands_

### Misc shortcuts
| Command | Description |
| ------- | ----------- |
| `Ctrl+Cmd+q` |  This shortcut locks the apple screen 
| `Cmd+opt+esc` |  This shortcut allows to force quit application 
### Terminal shortcuts
| Command | Description |
| ------- | ----------- |
| `Ctrl+u` |  This shortcut clears the entirety of the line before the cursor

### Navigation
| Command | Description |
| ------- | ----------- |
| `cd ..` |  move to parent directory of current directory
| `cd /` | move to the root directory
| `cd -` | move to the previous working directory
### list files and directories
| Command | Description |
| ------- | ----------- |
| `pwd` | print working/current directory |
| `ls` |  list files/directories(aka folders) in current directory|
| `ls /` |  list files/directories(aka folders) of the root directory|
| `ls ~` |  list files/directories(aka folders) of user home directory|
| `ls ..` |  list files/directories(aka folders) of parent directory of current directory|
| `ls -a` |  list files/directories(aka folders) of current directory including hidden files/directories|
| `ls -l` |  long listing of files/directories of current directory|
| `ls -t` |  list files/folders sorted by modification date descending|
| `ls -r` |  list files/folders in reversed fashion|
| `ls -R` |  list the contents of a directory and all its subdirectories|

### Create soft and hard links
| Command | Description |
| ------- | ----------- |
| `ls -i` |shows the index node number of files/directories in the current directory|
| `ls -i /` |shows the i-node number of files/directories in the root directory|
| `ls -s <original file/directory> <soft file/directory>` | Create soft link file/directory for original file/directory.|
| `ls <original file> <hard file>` | Create hard link for file for original file.**Not supported for directories**|

### Working with files
| Command | Description |
| ------- | ----------- |
| `touch <filename>` | creates the file. **If file exists than it will change its timestamp**|
| `touch <filename1> <file2> <file3>` | creates the file1,file2 and file3|
| `mkdir <directoryname>` | creates the directory|
| `mkdir <directoryname1> <directoryname2> <directoryname3>` | Will create three directories|
| `rmdir <directoryname>` | removes the directory only **if it is empty**|
| `rm    <file/directoryname>` | removes the file/directory only **if directory is empty**|
| `rm -R/r <file/directoryname>` | removes the file/directory no matter if directory is empty or not.`R is case insensitive`|
| `cp <file1> <file2>` |Make a copy of file1 named as file2 |
| `cp -R <dir1> <dir2>` |Make a copy of dir1 named named as dir2.**R stands for recursive**|
| `cp <file1> <file1> <destination>` | copy multiple files into destination directory.*destination directory must exist*|
| `cp -R <dir1> <dir2> <destination>` | copy multiple directories into destination directory.*destination directory must exist*| 
| `mv <file1/dir1> <file2/dir2>` |This is will rename file1/dir1 to file2/dir2 |
| `mv file1 file2 ..... destination` |This will move multiple files to destination directory.**The directory must exist**|
| `file yourfile` |Print brief description of file's content and will reveal the file type,**Linux has no concept of file extension**|

iTerm2 Commands
===============
| Command | Description |
| ------- | ----------- |
| `Shift+Cmd+]` |  This shortcut switch to next tab
| `Shift+Cmd+[` |  This shortcut switch to previous tab
