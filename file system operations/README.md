# File System Operations Lab Exercises

This workspace contains three lab exercises for file system operations in Node.js.

## Lab Exercise 1: File Manager Application

A command-line application for basic file operations.

### Usage

```bash
cd lab1-file-manager
npm start list <directory>
npm start read <file>
npm start write <file> "<content>"
npm start copy <source> <destination>
npm start delete <file>
```

### Commands

- `list <directory>`: List contents of a directory
- `read <file>`: Display file contents
- `write <file> <content>`: Write content to a file
- `copy <source> <destination>`: Copy a file
- `delete <file>`: Delete a file

## Lab Exercise 2: Log File Analyzer

A program that analyzes log files and generates statistics.

### Usage

```bash
cd lab2-log-analyzer
npm start <logfile>
```

The program reads the log file using streams and counts ERROR, WARN, and INFO messages.

## Lab Exercise 3: File Synchronization Tool

A utility that synchronizes files between two directories.

### Usage

```bash
cd lab3-file-sync
npm start <sourceDir> <destDir>
```

The tool compares files by modification time and size, copying newer or missing files from source to destination.

## Pushing to Git Repositories

Each lab has been initialized as a separate Git repository with an initial commit. To push to GitHub or another remote repository:

1. Create a new repository on GitHub (or your preferred Git hosting service) for each lab
2. For each lab directory, add the remote and push:

```bash
# For Lab 1
cd lab1-file-manager
git remote add origin https://github.com/yourusername/file-manager.git
git push -u origin main

# For Lab 2
cd ../lab2-log-analyzer
git remote add origin https://github.com/yourusername/log-analyzer.git
git push -u origin main

# For Lab 3
cd ../lab3-file-sync
git remote add origin https://github.com/yourusername/file-sync.git
git push -u origin main
```

Replace `yourusername` with your actual GitHub username and adjust repository names as needed.