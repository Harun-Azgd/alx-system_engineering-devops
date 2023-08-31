#!/bin/bash
su > switches the current user
id -un > prints the effective username of the current user
groups > prints all the groups the current user is part of
sudo chown > changes the owner of the file
touch > creates an empty file
chmod u+x  > adds execute permission to the owner of the file
chmod +114 > adds execute permission to the owner and the group owner, and read permission to other users, to a file
chmod +x > adds execution permission to the owner, the group owner and the other users, to the file
chmod 007 > sets the permission to Owner: no permission at all
Group: no permission at all
Other users: all the permissions
chmod 753 > sets the mode of the file
