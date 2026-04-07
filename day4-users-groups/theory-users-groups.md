# Day 4 - Users, Groups and Sudo

## What I learned

Today I learned how users, groups, and permissions work together in Linux.

------------------------------------------------------------------------

## Users

Each action in Linux is performed by a user.

Types:
- normal user
- root user (administrator)

Command:
```bash
whoami
```

------------------------------------------------------------------------

## Sudo

The `sudo` command allows a normal user to execute commands as root.

Example
```bash
sudo apt update
```
------------------------------------------------------------------------

## Groups

Groups are used to manage permissions for multiple users.

Commands:
```bash
groups
id
```

------------------------------------------------------------------------

## Managing users and groups

Create user:
```bash
sudo adduser username
```

Create group:
``` bash
sudo groupadd groupname
```

Add user to group
```bash
sudo usermod -aG groupname username
```

------------------------------------------------------------------------

## File ownership

Change owner:
```bash
sudo chown user file.txt
```

Change group:
```bash
sudo chgrp group file.txt
```

------------------------------------------------------------------------

## Summary

Day 4 helped me understand how users, groups, and sudo work together with Linux permissions.



