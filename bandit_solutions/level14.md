# Bandit Level 14  

**Goal**: The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level  

**Commands used**:  
`cd /home/bandit13`  
`ls`  
`ssh bandit14@bandit.labs.overthewire.org -p 2220 -i sshkey.private`  
