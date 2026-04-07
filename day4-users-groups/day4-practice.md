# Day 4 - Practice

## Screenshots

Below are examples of working with users, groups, and file ownership in Linux.

![Users and groups 1](../images/day4-users-groups-1.png)
![Users and groups 2](../images/day4-users-groups-2.png)

## What I did

- checked current user and groups  
- created a new user and groups  
- added users to a group  
- verified group membership  
- created test files  
- changed file owner and group  

## Commands used

```bash
whoami                                  # show current user
id                                      # show user id and groups
sudo adduser patreus                    # create new user
sudo groupadd security                  # create new group
sudo usermod -aG security ubupat        # add user to group
sudo chown patreus onlypatreus.txt      # change file owner
sudo chgrp security security-gr.txt     # change file group
```
