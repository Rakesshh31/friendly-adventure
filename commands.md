Here’s the list with numbering:

---

# **Linux Commands Cheat Sheet**

### **Basic System Commands**
1. **`whoami`**  
   Displays the current logged-in user.
  
2. **`date`**  
   Shows the current system date and time.

3. **`uptime`**  
   Shows how long the system has been running and the system load.

4. **`clear`**  
   Clears the terminal screen.

### **Navigating Directories**
5. **`cd /`**  
   Changes the current directory to the root directory.

6. **`pwd`**  
   Prints the current working directory.

7. **`ls`**  
   Lists all files and directories in the current directory.

8. **`cd bin`**  
   Changes the current directory to the `bin` folder.

9. **`cd ..`**  
   Moves up one directory level (to the parent directory).

### **File and Directory Management**
10. **`mkdir devops`**  
    Creates a new directory named `devops`.

11. **`touch hello.txt`**  
    Creates a new empty file named `hello.txt`.

12. **`echo "hello dosto" > hello.txt`**  
    Writes the text `hello dosto` to `hello.txt`.

13. **`cat hello.txt`**  
    Displays the contents of `hello.txt`.

14. **`rm hello.txt`**  
    Deletes the `hello.txt` file.

15. **`mkdir -p devops/newlow/mitra`**  
    Creates nested directories `newlow` and `mitra` inside `devops`.

16. **`chmod 700 filename`**  
    Changes permissions of `filename` so only the owner has full access.

### **Text Editing and Viewing**
17. **`vim hello.txt`**  
    Opens the file `hello.txt` for editing in Vim.

18. **`nano demo.txt`**  
    Opens the file `demo.txt` for editing in Nano.

19. **`head hello.txt`**  
    Displays the first few lines of the `hello.txt` file.

### **Package Management**
20. **`sudo apt install nginx`**  
    Installs the Nginx web server.

21. **`cd /var/www/html`**  
    Navigates to the web root folder for Nginx.

22. **`vim index.nginx-debian.html`**  
    Opens the default Nginx webpage for editing in Vim.

### **File Permissions**
23. **`chmod +x second.sh`**  
    Makes the script `second.sh` executable.

24. **`chmod 777 devops_first.sh`**  
    Grants read, write, and execute permissions to everyone for the `devops_first.sh` script.

25. **`chmod 700 bolo.txt`**  
    Grants full permission to the owner, but restricts others from accessing `bolo.txt`.

### **Working with Scripts**
26. **`nano devops_first.sh`**  
    Opens the script `devops_first.sh` in Nano for editing.

27. **`bash devops_first.sh`**  
    Executes the `devops_first.sh` script using Bash.

28. **`./second.sh`**  
    Runs the executable `second.sh` script.

29. **`./compare.sh`**  
    Executes the `compare.sh` script.

30. **`chmod +x createDirectories.sh`**  
    Makes the `createDirectories.sh` script executable.

31. **`./createDirectories.sh day 1 90`**  
    Runs the `createDirectories.sh` script to create directories named `day1` through `day90`.

### **Finding Common Elements in Files**
32. **`comm -12 <(sort Cricketrs.txt) <(sort bolo.txt)`**  
    Finds and displays common lines between `Cricketrs.txt` and `bolo.txt`.

33. **`sed -i '1i Don Bradman' Cricketrs.txt`**  
    Inserts `Don Bradman` at the beginning of the `Cricketrs.txt` file.

### **Monitoring and Services**
34. **`sudo systemctl status nginx`**  
    Checks the status of the Nginx service.

### **Miscellaneous Commands**
35. **`history | tail -10`**  
    Shows the last 10 commands executed in the terminal.

36. **`exit`**  
    Exits the current terminal session.

### **Example of Working with a Script**
- **Create directories using a script**:
    37. **`nano createDirectories.sh`**: Create a script for making directories.
    38. **`chmod +x createDirectories.sh`**: Make the script executable.
    39. **`./createDirectories.sh day 1 90`**: Run the script to create directories named `day1` to `day90`.

- **Delete directories using a command**:
    40. **`rm -r day{1..90}`**: Deletes directories `day1` to `day90`.

---

This version includes numbered commands for easy reference!
