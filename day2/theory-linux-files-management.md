# Day 2 - Linux File Management

## What I learned

Today I learned how to manage files and directories in Linux using terminal commands.

------------------------------------------------------------------------

## Creating files and directories

Linux allows me to create both directories and empty files directly from the terminal.

Commands:
- `mkdir` - create a new directory
- `touch` - create a new empty file

Example:
```bash
mkdir my-new-folder
touch my-notes.txt
```

------------------------------------------------------------------------

## Copying files and directories

I learned how to copy files and folders from one place to another.

Commands:
- `cp` - copy a file
- `cp source destination` - copy file to another location
- `cp -r` - copy a directory recursively

Example:
```bash
cp my-notes.txt my-notes_copy.txt
cp my-notes.txt folder/
cp -r projects backup_projects
```

------------------------------------------------------------------------

## Moving and renaming

I learned that the same command can be used both to move files and to rename them.

Commands:
- `mv` - move file or directory
- `mv oldname newname` - rename a file or directory

Example:
```bash
mv notes.txt documents/
mv old-name.txt new-name.txt
```

------------------------------------------------------------------------

## Removing files and directories

Linux also allows me to remove files and folders from the terminal.

Commands:
- `rm` - remove file
- `rm -r` - remove directory and its contents

Example:
```bash
rm notes.txt
rm -r old-folder
```

------------------------------------------------------------------------

## Working with multiple files

I learned that Linux can work with many files at once using patterns.

Commands:
- `*` - match many files
- `*.txt` - all files ending with `.txt`
- `*.log` - all files ending with `.log`

Example:
```bash
rm notes1.txt notes2.txt
mv *.txt backup/
cp *.log logs/
```

------------------------------------------------------------------------

## Understanding paths in file management

When copying, moving, or deleting files, Linux uses paths.

### Relative path

A path based on where I currently am.

Example:
```bash
cp notes.txt backup/
```

### Absolute path

A full path starting from `/`.

Example:
```bash
cp /home/ubupat/notes.txt /home/ubupat/backup/
```

------------------------------------------------------------------------

## Working with folders and destinations

I learned that Linux commands usually follow this logic:

Example:
```bash
cp file.txt backup/
mv report.txt documents/
```

Meaning:
```bash
command source destination
```

This helped me understand that:
- the first part is what I want to copy or move
- the second part is where I want to place it

------------------------------------------------------------------------

## USB drive as a directory

I learned that in Linux, a USB drive is treated like a normal mounted directory.

Example:
```bash
/media/ubupat/USB_NAME
```

Commands:
```bash
cp notes.txt /media/ubupat/USB_NAME/
mv project/ /media/ubupat/USB_NAME/
```

This means I can use the same commands for normal folders and USB storage.

------------------------------------------------------------------------

## Key concept - file operations depend on paths

I learned that file management in Linux is based on:
- file names
- directory names
- source and destination paths
- patterns like `*`

This means that Linux does not need a graphical interface to manage files efficiently.

------------------------------------------------------------------------

## Linux commands to remember

- `mkdir` - creates directories
- `touch` - creates empty files
- `cp` - copies files and directories
- `mv` - moves or renames files
- `rm` - removes files
- `rm -r` - removes directories
- `*` - helps work with many files at once
- file operations depend on correct paths

------------------------------------------------------------------------

## Summary

Day 2 helped me understand how to create, copy, move, rename, and remove files and directories in Linux. It also showed me how important paths are in everyday terminal work.
