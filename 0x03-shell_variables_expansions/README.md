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
export BEST="School" > creates a new global variable
echo $((128 + $TRUEKNOWLEDGE)) >  prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE
echo $(($POWER / $DIVIDE)) >  prints the result of POWER divided by DIVIDE
echo $(($BREATH ** $LOVE)) > displays the result of BREATH to the power LOVE
                             BREATH and LOVE are environment variables
echo $((2#$BINARY)) > converts a number from base 2 to base 10
echo {a..z} {a..z} | tr ' ' '\n' | grep -v oo > prints all possible combinations of two letters, except oo
