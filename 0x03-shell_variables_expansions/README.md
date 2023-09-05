#!/bin/bash
alias ls="rm *" >  script that creates an alias.
                   Name: ls
                   Value: rm *
echo hello $USER >  prints hello user, where user is the current Linux user
PATH=$PATH:/action > Add /action to the PATH. /action
echo $PATH | tr ":" "\n" | wc -l > counts the number of directories in the PATH
printenv > lists environment variables
set > lists all local variables and environment variables, and functions
BEST="School" > creates a new local variable
