# Unix Commands from Workshop 11 Nov 2021

commands (BASH shell — most basic shell)

## asterix symbol = list
* whoami
* date
* pwd (present working directory)
* ls (show content of folder you are in)
* cd Desktop (change directory to the desktop)
* pwd (confirm desktop is directory)
* ls (show stuff on desktop)
## number 1. = numbered listing
1. mkdir 2021-11-11-ubimotif (make a folder on the desktop)
1. ls (show your new folder you made)
1. cd 2021-11-11-ubimotif (to move to this directory)
1. cd - (moves you back to Desktop)
# checklist is * [ ] 
* [ ] cd - (two times, moves you back to your old folder, a way to jump between two folders)
* [ ] cd .. (moves you back a folder)
* [ ] ls -F (shows folder files via / symbol)
* [ ] ls -a (shows hidden files)
# checked checklist * [x]
* [x] man ls (opens ls manual; can also google online if it is unclear)
* [x] ls
* [x] cd Desktop/shell-lesson-data (go to the shell lesson data directory)
* [x] if you are ALREADY in the Desktop, then type cd shell-lesson-data
* ls (check whats in there)
* ls -a
* ls -F
* less notes.txt (we want to look at this file)
* Q (quit the file)
* less numbers.txt
* less (command to read a file, but not using all your memory to open the entire thing)
* pwd (/Users/msharan/Desktop/shell-lesson-data -- this an absolute path)
* ls -tlr (all items on desktop, sorted by time, with long name, in reverse order)
* pwd
* mkdir (make a folder)
* mkdir 'notes and stuff' (quotations enable use of spaces)
* cd ../.. (go back up two levels up)
* ls / (list all folders)
* ls /Users/fredastaire/Desktop/shell-lesson-data (list all items in that folder)
* ls -art (all files, in reverse, according to time)
* nano blabla.txt (command to create a file i.e. blabla.txt)
* ctrl + O (to save the file)
* ctrl + X (to exit file)
* mv blabla.txt DONTOPEN.txt (function one of mv -- to rename something)
* mv DONTOPEN.txt ../trash (function two of mv -- move something to the trash folder above)
* cp (copy command ONLY FOR FILES)
* rm (remove command)
* always ls to check whats in there
* touch EMPTY.txt (to create an empty file)
* cp -r trash (copy command FOR FOLDERS)
* rm -ir trash/
* mv data 2021-11-11-ubimotif
