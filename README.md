# ubuntu-commands
List of all commands used in terminal

## File and Directory Management
- **`ls`**: Lists files and directories in the current directory.
- **`cd`**: Changes the current directory.
- **`pwd`**: Prints the current working directory.
- **`mkdir`**: Creates a new directory.
- **`rmdir`**: Removes an empty directory.
- **`rm`**: Removes files or directories.
- **`cp`**: Copies files or directories.
- **`mv`**: Moves or renames files or directories.
- **`touch`**: Creates an empty file or updates the timestamp of an existing file.
- **`find`**: Searches for files and directories.
- **`locate`**: Finds files by name.

## File Viewing and Editing
- **`cat`**: Concatenates and displays file content.
- **`less`**: Views file content one screen at a time.
- **`more`**: Views file content one screen at a time (less advanced than `less`).
- **`head`**: Displays the first few lines of a file.
- **`tail`**: Displays the last few lines of a file.
- **`nano`**: Simple text editor.
- **`vim`**: Advanced text editor.
- **`gedit`**: Graphical text editor.

## File Compression and Archiving
- **`tar`**: Archives files (e.g., `tar -cvf archive.tar directory`).
- **`gzip`**: Compresses files.
- **`gunzip`**: Decompresses files.
- **`zip`**: Compresses files into a ZIP archive.
- **`unzip`**: Extracts files from a ZIP archive.

## System Information and Management
- **`uname`**: Displays system information.
- **`top`**: Displays running processes.
- **`htop`**: Interactive process viewer (more advanced than `top`).
- **`ps`**: Displays a snapshot of current processes.
- **`df`**: Displays disk space usage.
- **`du`**: Displays directory space usage.
- **`free`**: Displays memory usage.
- **`uptime`**: Shows how long the system has been running.
- **`who`**: Shows who is logged into the system.

## User Management
- **`adduser`**: Adds a new user.
- **`deluser`**: Deletes a user.
- **`passwd`**: Changes a user's password.
- **`usermod`**: Modifies user account information.
- **`groupadd`**: Adds a new group.
- **`groupdel`**: Deletes a group.
- **`groups`**: Shows the groups a user is a member of.

## Package Management
- **`apt update`**: Updates the package list.
- **`apt upgrade`**: Upgrades all installed packages to their latest versions.
- **`apt install`**: Installs a package.
- **`apt remove`**: Removes a package.
- **`apt purge`**: Removes a package and its configuration files.
- **`apt autoremove`**: Removes unnecessary packages.

## Networking
- **`ifconfig`**: Displays network interfaces (deprecated, use `ip`).
- **`ip`**: Manages network interfaces and routing.
- **`ping`**: Tests connectivity to a host.
- **`netstat`**: Displays network connections, routing tables, interface statistics (deprecated, use `ss`).
- **`ss`**: Displays socket statistics.
- **`wget`**: Downloads files from the web.
- **`curl`**: Transfers data from or to a server.

## Permissions and Ownership
- **`chmod`**: Changes file permissions.
- **`chown`**: Changes file owner and group.
- **`chgrp`**: Changes group ownership of a file.

## Disk Management
- **`mount`**: Mounts a filesystem.
- **`umount`**: Unmounts a filesystem.
- **`fdisk`**: Disk partitioning tool.
- **`mkfs`**: Creates a filesystem on a device.
- **`fsck`**: Checks and repairs a filesystem.

## Search and Filter
- **`grep`**: Searches text using patterns.
- **`awk`**: Pattern scanning and processing language.
- **`sed`**: Stream editor for filtering and transforming text.
- **`sort`**: Sorts lines of text files.
- **`uniq`**: Reports or filters out repeated lines in a file.

## System Monitoring and Performance
- **`dmesg`**: Prints kernel and boot messages.
- **`vmstat`**: Reports virtual memory statistics.
- **`iostat`**: Reports CPU and I/O statistics.
- **`sar`**: Collects, reports, or saves system activity information.

## Miscellaneous
- **`echo`**: Displays a line of text.
- **`date`**: Displays or sets the system date and time.
- **`cal`**: Displays a calendar.
- **`history`**: Displays the command history.
- **`alias`**: Creates an alias for a command.
- **`kill`**: Sends a signal to a process.
- **`xkill`**: Forces a window to close.
