# Bash Command Line Tutorial

## The Command Line

CLI is a text based interface to the system where commands can be typed

Shells within the terminal defines the behavior of the terminal and looks after executing commands. Bash is the most common shell. Zsh is the one being used.

`echo $SHELL` can be input into the terminal to determine what shell is being used

The up arrow key will traverse through a 'list' of previously used commands so there is no need to retype them. The left/right arrow keys can be used to edit the commands.

The TAB key can be used to complete the path names while typing

## Basic Navigation

`pwd` is to Print Working Directory - helps determine location in the terminal

`ls` is for List - gives the list of files in the current directory. It can be used with

* ` -l `
* `/etc`

root directories are indicated with a single /

absolute paths denote a location and start with a /

relative paths denote a location as well but do not start with a /

* ~ (tilde) will get you to the home directory
* . (dot) will reference the current directory
* .. (dot dot) will get you to the parent directory of the current directory

`cd` is Current Directory and can be used to move between locations

## More About Files

With a computer, everything under the hood is a file; even the hardware

a file extension is two to four characters after a file that determine what type of file it is

case sensitivity is important when dealing with files; also be careful when using spaces. When using spaces with a file name in the terminal, quotes around the entire name helps and the escaping(\) the space in the middle also works

Hidden files begin with a . (full stop); `ls -a` ran in the terminal will show all files including hidden files

## Manual Pages

The manual pages gives commands that can be ran and the explanation of what they do

`man <command to look up>` will run the manual pages for that particular command

`man -k <search term>` can be used for a keyword search in the manual pages

To search within the manual pages, press forward slash '/' followed by the term you would like to search for and hit 'enter' If the term appears multiple times you may cycle through them by pressing the 'n' button for next.

long hand command line options begin with two dashes ( -- ) and short hand options begin with a single dash ( - ). Long hand is easier to read while short hand can chain together

## File Manipulation

`mkdir` makes a directory or file folder (mkdir *options* **Directory**)

Options:

* -p which tells mkdir to make parent directories as needed
* -v which makes mkdir tell us what it is doing

`rmdir` removes a directory and cannot be undone

`touch` creates a blank file

NOTE: touch is actually a command we may use to modify the access and modification times on a file

`cp` copies a file or directory

* `cp` can use -r to copy all the files

`mv` moves files

`rm` removes a file and cannot be undone

* When rm is run with the -r option it allows us to remove directories and all files and directories contained within

## [Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)

Follow link in header for access to the cheat sheet.
