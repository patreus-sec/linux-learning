# Day 1 - Linux Basics and Navigation

## What I learned

Today I started learning Linux from scratch and focused on understanding
how to navigate the system using the terminal.

------------------------------------------------------------------------

## Terminal basics

Example prompt: 
```bash
ubupat@ubuntu-pc:\~\$
```

Meaning: 
ubupat - current user
ubuntu-pc - computer name
~ - home directory
$ - normal user (not root)

------------------------------------------------------------------------

## Linux file system structure

Linux uses a tree-like structure starting from the root directory `/`.

Example:
```bash
/
├── home
│   └── ubupat
├── etc
├── var
├── tmp
```

Important directories:

- / - root of the system
- /home - user directories
- /home/ubupat - my home directory

------------------------------------------------------------------------

## Commands I learned

### Navigation and location

-   pwd - show current directory
-   ls - list files and folders
-   ls -la - detailed list including hidden files

### Changing directories

-   cd folder - go into a folder
-   cd .. - go one level up
-   cd \~ - go to home directory
-   cd / - go to root directory

------------------------------------------------------------------------

## Understanding paths

### Relative path

A path based on where I currently am.

Example: 
```bash
cd Documents
```

### Absolute path

A full path starting from `/`.

Example: 
```bash
cd /home/ubupat/Documents
```

------------------------------------------------------------------------

## Key concept - parent directory

I learned that: - .. always means go to the parent directory - it does
not choose between folders - it always goes one level up

Example: 
```bash
/home/ubupat/Projects
cd ..
```
Result: 
```bash
/home/ubupat
```

------------------------------------------------------------------------

## Key things I understood

-   Linux uses a hierarchical file system
-   / is the starting point
-   ~ is my home directory
-   cd is navigation
-   pwd shows location
-   ls shows contents
-   .. moves one level up

------------------------------------------------------------------------

## Summary

Day 1 was about understanding Linux structure and navigation.
