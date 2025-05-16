

Here is a categorized list of essential and commonly used **CMD (Command Prompt) commands** for Windows:

---

### 🖥️ **System Information & Configuration**

| Command                  | Description                                      |
| ------------------------ | ------------------------------------------------ |
| `systeminfo`             | Displays detailed configuration of the computer. |
| `hostname`               | Shows the name of the current computer.          |
| `ipconfig`               | Displays IP address and network info.            |
| `ipconfig /all`          | Shows detailed network configuration.            |
| `tasklist`               | Lists all running processes.                     |
| `taskkill /PID <pid> /F` | Kills a process by PID.                          |
| `set`                    | Displays environment variables.                  |
| `echo %USERNAME%`        | Shows the current user name.                     |

---

### 📁 **File and Directory Operations**

| Command                             | Description                               |
| ----------------------------------- | ----------------------------------------- |
| `dir`                               | Lists files and directories.              |
| `cd`                                | Changes current directory.                |
| `cd ..`                             | Goes up one directory level.              |
| `md <folder>` / `mkdir <folder>`    | Creates a new folder.                     |
| `del <file>`                        | Deletes a file.                           |
| `rmdir <folder>`                    | Deletes a folder (if empty).              |
| `xcopy <source> <dest> /E /H /C /I` | Copies folders and files with subfolders. |
| `move <source> <dest>`              | Moves files or folders.                   |

---

### 🔒 **User and Security**

| Command                                         | Description                      |
| ----------------------------------------------- | -------------------------------- |
| `net user`                                      | Lists all user accounts.         |
| `net user <username> <password> /add`           | Creates a new user.              |
| `net localgroup administrators <username> /add` | Adds user to Admin group.        |
| `whoami`                                        | Displays current logged in user. |

---

### 🌐 **Network**

| Command              | Description                          |
| -------------------- | ------------------------------------ |
| `ping <hostname>`    | Tests network connectivity.          |
| `tracert <hostname>` | Shows route taken to reach the host. |
| `netstat -an`        | Displays open ports and connections. |
| `nslookup <domain>`  | Queries DNS records.                 |

---

### 🛠️ **System Utilities**

| Command               | Description                            |
| --------------------- | -------------------------------------- |
| `sfc /scannow`        | Scans and fixes system file integrity. |
| `chkdsk`              | Checks disk for errors.                |
| `diskpart`            | Opens disk partition tool.             |
| `shutdown /s /f /t 0` | Shuts down the PC immediately.         |
| `shutdown /r /f /t 0` | Restarts the PC immediately.           |
| `cleanmgr`            | Opens Disk Cleanup.                    |

---
