#Bandit Level 13  

**Goal**: he password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work. Use mkdir with a hard to guess directory name. Or better, use the command “mktemp -d”. Then copy the datafile using cp, and rename it using mv (read the manpages!)  

**Commands used**:  
`cd /tmp`  
`mkdir mktemp`  
`cd /home/bandit12`  
`cp data.txt /tmp/mktemp`  
`cd /tmp/mktemp`  
`mv data.txt data2.txt`  
