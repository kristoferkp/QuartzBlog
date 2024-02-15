A file system is a way of organizing and retrieving files from storage media, like hard drives or SSDs. In Linux, this organization is hierarchical, meaning it's structured in a tree-like manner with directories and sub-directories.

Key Directories and Their Roles
- /bin, /sbin - Essential binaries for system booting and operations.
- /etc - System-wide configuration files and application preferences.
- /home - User home directories, holding personal files and settings. Each user gets a directory under /home (e.g., /home/user1, /home/user2)
- /lib, /lib64 - Shared libraries for program execution.
- /usr - User-related programs, libraries, and documentation.
- /var - Variable data like logs, temporary files, and spools.
- /tmp - Temporary files created by processes.
- /dev - Device files representing hardware components. This includes sda1, sda2, and sda3, which are physical drives mounted on the system.
- /proc, /sys - Virtual file systems providing real-time system data.
- /root - The home directory for the root user (system administrator). It's a private space for system administration tasks and is not to be confused with the root (/) of the filesystem. (During CTFs, many flags are often hidden here.)