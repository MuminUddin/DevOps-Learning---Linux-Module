# Linux Module Notes  

## 📌 **Core Commands Cheatsheet**  
| Command | Description | Example |  
|---------|-------------|---------|  
| `ls`    | List directory contents | `ls -la` (show hidden files) |  
| `chmod` | Change file permissions | `chmod 600 key.pem` (restrict access) |  
| `grep`  | Search text patterns | `grep "error" log.txt` |  
| `find`  | Locate files/dirs | `find / -type f -name "*.conf"` |  
| `touch` | Creates file in current directory | `touch myfile` |  




## 🔍 **Key Concepts Explained**  
### **File Systems**  
- **/**: Represents the root directory
- **bin directory**: Contains essential binary executables
- **boot directory**: Contains files related to the booting process including the linux kernel
- **dev directory**: Holds device files. Special files that represent devices attached to the system e.g disks and terminal
- **etc directory**: Contains system wide configuration file and shell scripts used to boot and initialise file systems
- 



### **File Permissions**  
- **Numeric codes**: `755` = `rwxr-xr-x`
- **Symbolic notation**: `chmod u+x script.sh` (add execute for user)


### **Pipes (`|`) and Redirection**  
- **Why**: Chain commands (e.g., `cat file \| grep "pattern" > output.txt`)
