# Bandit Level 12  

**Goal**: The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions  

**Commands used**:  
`cat data.txt | tr -t 'abcdefghijklmnopqrstuvwxyz' "nopqrstuvwxyzabcdefghijklm" | tr -t 'ABCDEFGHIJKLMNOPQRSTUVWXYZ' "NOPQRSTUVWXYZABCDEFGHIJKLM"`  

**Password**:  
`7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4`
