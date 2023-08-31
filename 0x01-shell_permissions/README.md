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
chmod --reference=olleh hello  > sets the mode of the file hello the same as olleh’s mode
chmod -R +X > adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
mkdir -m 751 my dir > creates a directory called my dir with permissions 751 in the working directory
chgrp > changes the group owner
chown vincent:staff * > changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
chown -h vincent:staff _hello > changes the owner and the group owner of _hello to vincent and staff respectively
chown --from=guillaume betty hello > changes the owner of the file hello to betty only if it is owned by the user guillaume

