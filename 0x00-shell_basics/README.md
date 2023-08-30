#!/bin/bash
pwd > prints the absolute path name of the current working directory
ls >  lists  contents of a file or a directory
cd ~user name > changes the working directory to the user’s home directory
ls -l > Display current directory contents in a long format
ls -al > Display current directory contents, including hidden files Using the long format
ls -lna > Display current directory contents in, Long format, with user and group IDs displayed numerically and hidden files
mkdir > creates a directory
mv > moves a file
rm > deletes a file
rm -r > deletes a directory
cd - > changes the working directory to the previous one
ls -al . ../boot > lists all files in the current directory and the parent of the working directory and the /boot directory, in long format
file > prints the type of the file
ln -s > Create a symbolic link
cp -un*.html ../ > copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer
mv [[:upper:]]* /tmp/u >  moves all files beginning with an uppercase letter to the directory /tmp/u
rm *~ > deletes all files in the current working directory that end with the character ~
mkdir -p welcome/to/school > creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory
ls -amvp > list all files and directories  br seperating with commas, sorting digits and letters, showing hidden files, directories name should end with slash and only digits and letters are used to sort in which digits should come first
