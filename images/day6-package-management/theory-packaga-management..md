# Day 6 - Package Management

## What I learned

Today I learned how to manage packages in Linux using APT.

------------------------------------------------------------------------

## What is a package

A package is a program along with all required files and dependencies.

Examples:
- git
- curl
- htop

------------------------------------------------------------------------

## Updating package list

Command:
```bash
sudo apt update
```

- downloads information about available packages

------------------------------------------------------------------------

## Upgrading system

Command:
```bash
sudo apt upgrade
```

- updates installed packages to newer versions

------------------------------------------------------------------------

## Installing packages

Command:
```bash
sudo apt install htop
```

- installs a package

------------------------------------------------------------------------

## Removing packages

Command:
```bash
sudo apt remove htop
```

- removes a package but keeps configuration files

Force remove:
```bash
sudo apt purge htop
```

- removes package with configuration

------------------------------------------------------------------------

## Searching packages

Command:
```bash
apt search htop
```

- finds packages in repository

------------------------------------------------------------------------

## Summary

Day 6 helped me understand how to install, update, and remove software in Linux.
