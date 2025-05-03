# Bandit Level 13  

**Goal**: he password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed. For this level it may be useful to create a directory under /tmp in which you can work. Use mkdir with a hard to guess directory name. Or better, use the command “mktemp -d”. Then copy the datafile using cp, and rename it using mv (read the manpages!)  

**Commands used**:  
`cd /tmp`  
`mkdir mktemp`  
`cd /home/bandit12`  
`cp data.txt /tmp/mktemp`  
`cd /tmp/mktemp`  
`mv data.txt data2.txt`  
`cp data2.txt data3.txt`  
`xxd -r data2.txt data3.txt`  
`file data3.txt`  
`mv data3.txt data3.bin.gz`  
`gunzip data3.bin.gz`  
`file data3.bin`  
`mv data3.bin data4.bin.bz`  
`bunzip2 data4.bin.bz`
`file data4.bin`  
`mv data4.bin data5.bin.gz`  
`gunzip data5.bin.gz`  
`file data5.bin`  
`tar -xf data5.bin`  
`file data6.bin`  
`tar -xf data6.bin`  
`file data6.bin`  
`mv data6.bin data7.bin.bz`  
`bunzip2 data7.bin.bz`  
`file data7.bin`  
`tar -xf data7.bin`  
`file data8.bin`  
`mv data8.bin data9.bin.gz`  
`gunzip data9.bin.gz`  
`file data9.bin`  
`cat data9.bin`  

**Password**:  
`FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn`
