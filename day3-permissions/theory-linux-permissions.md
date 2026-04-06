# Day 3 - Linux Permissions

## What I learned

Today I learned how Linux permissions work for files and directories.

------------------------------------------------------------------------

## Permission groups

Linux permissions are divided into three categories:

- `user` - the owner of the file
- `group` - the group assigned to the file
- `others` - all other users

------------------------------------------------------------------------

## Permission types

There are three basic permissions:

- `r` - read
- `w` - write
- `x` - execute

For files:
- `r` means the file can be read
- `w` means the file can be modified
- `x` means the file can be executed

For directories:
- `r` means the directory contents can be listed
- `w` means files can be created, deleted, or renamed inside
- `x` means the directory can be entered

------------------------------------------------------------------------

## Viewing permissions

Command:
```bash
ls -l      # list files with permissions and details
```

Example:
```bash
-rw-r--r-- 1 ubupat ubupat 123 Sep 10 10:00 notes.txt
drwxr-xr-x 2 ubupat ubupat 4096 Sep 10 10:05 scripts
```

The first character shows the type:
- `-` = regular file
- `d` = directory

The next nine characters are grouped into:
- owner permissions
- group permissions
- others permissions

Example:
```bash
rw- r-- r--
```

------------------------------------------------------------------------

## Numeric permission values

Linux permissions can also be written as numbers:

- `r = 4`
- `w = 2`
- `x = 1`

Examples:
- `7 = rwx`
- `6 = rw-`
- `5 = r-x`
- `4 = r--`

------------------------------------------------------------------------

## Changing permissions

Command
```bash
chmod     # change file permissions
```

Examples:
```bash
chmod 644 file.txt
chmod 755 script.sh
chmod u+x script.sh
chmod o-r secret.txt
```

Meaning:

- `u` = user
- `g` = group
- `o` = others
- `a` = all users

------------------------------------------------------------------------

## Common permission examples

- `644` - normal text file
- `600` - private file
- `755` - executable script
- `700` - private directory

------------------------------------------------------------------------

## Summary

Day 3 helped me understand how to read and change Linux permissions using `ls -l` and `chmod`.







