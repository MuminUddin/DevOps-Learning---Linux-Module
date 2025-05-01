# Bandit Level 7  

**Goal:** The password for the next level is stored somewhere on the server and has all of the following properties:  

- owned by user bandit7  
- owned by group bandit6  
- 33 bytes in size

**Commands used:**  
`find / -size 33c -group bandit6 -user bandit7 2>/dev/null`  
`cat /var/lib/dpkg/info/bandit7.password`  

**Password:**  
`morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj`
