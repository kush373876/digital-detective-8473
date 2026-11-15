# Mission 3 – Understand the Operating System

## Objective
To understand how an operating system manages processes, memory, storage, files, devices, users, and permissions.

## Task 3.1 – System Information and Activity

### Commands Used

```bash
sw_vers
whoami
df -h /
top -l 1 -n 10
```

### Observations

- Operating System: macOS
- macOS Version: [Enter version from sw_vers]
- Active Account: [redacted]
- Available Storage: [Enter available storage from df -h /]
- System Activity: The top command displayed running processes and system activity, including CPU and memory information.

## Task 3.2 – Running Processes and PID

### Command Used

```bash
ps -axo pid,comm | head -n 15
```

### Understanding

A process is an instance of a program that is currently running on a computer.

PID stands for Process ID. It is a unique number assigned to each running process by the operating system.

### Examples

1. [Enter first process name from your output] – PID: [Enter PID]
2. [Enter second process name from your output] – PID: [Enter PID]

## Task 3.3 – Paths and File Permissions

### Commands Used

```bash
pwd
cd mission-03-operating-system
pwd
cd ..
ls -l mission-02-terminal/practice/notes.txt
```

### Absolute Path

An absolute path gives the complete location of a file or directory, starting from the root directory `/`.

Example: `/Users/username/digital-detective-8473/mission-03-operating-system/README.md`

### Relative Path

A relative path describes the location of a file from the current working directory.

Example: `mission-03-operating-system/README.md` when working from the project root.

### File Permissions

The `ls -l` command displays file permissions.

- `r` – Read permission
- `w` – Write permission
- `x` – Execute permission
- `-` – Permission not granted

The first three permission characters after the file type represent the owner's permissions.

## Task 3.4 – Responsibilities of an Operating System

### 1. Process Management
The operating system manages running programs and allocates CPU time to them.

Example: Running Chrome and VS Code simultaneously.

### 2. Memory Management
The operating system allocates and manages RAM for different applications.

Example: Providing memory to browser tabs and other applications.

### 3. Device Management
The operating system manages hardware devices through device drivers.

Example: Managing a keyboard, mouse, printer, or USB device.

### 4. File Management
The operating system organizes, stores, retrieves, and manages files and folders.

Example: Creating, saving, copying, and deleting files.

### 5. User Interface and Shell
The operating system provides interfaces through which users interact with the computer.

Example: Finder provides a graphical interface, while Terminal provides a command-line interface.

### 6. Security and Permissions
The operating system protects data and controls access to files and resources.

Example: File permissions determine who can read, write, or execute a file.

## Difficulties and Learning

- Learned how to check macOS system information.
- Understood how to view running processes and identify PIDs.
- Learned the difference between absolute and relative paths.
- Understood read, write, and execute permissions.
- Learned six important responsibilities of an operating system.

## Conclusion

This mission helped me understand how macOS manages system resources, running applications, files, hardware, and user permissions.