# Sublime-Squirrel
Original author is [micheg](https://github.com/micheg), [repository found here](https://github.com/micheg/sublime_squirrel).

This is Squirrel Programming Language support for Sublime Text 2 & 3.
I tried my best to expand the original repo a bit more and add a little structure to it.

## Changes
* Add highlight for most Squirrel functions (regexp(), lstrip(), format(), time(), .tointeger(), .tostring(), .len() and many, many more)
* Add highlight for specifiers (%s, %i etc.)
* Create folder structure
* Add snippets

## Note
Editing and messing around with these files is not in my area of expertise. I really wanted better support for the Squirrel highlighting in Sublime so I took a stab at it. 
It's not perfect and many sections can probably be improved upon, but it works so i'm happy with it for now. 

Feel free to improve where needed and share!

## Installation
There are 2 ways to install it.

* Git Clone
* File Download

### Git Clone
I'm on Windows, so OS X and Ubuntu might not be 100% correct.

Open up your Sublime Text packages directory and clone the repository using the commands below:

on Windows (using Git Bash):

    cd ~/AppData/Roaming/Sublime\ Text\ 2/Packages
    or
    cd ~/AppData/Roaming/Sublime\ Text\ 3/Packages
    git clone https://github.com/iAmRoland/Sublime-Squirrel.git Squirrel

on OS X (are the paths correct?):
    
    cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages
    or
    cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages
    git clone https://github.com/iAmRoland/Sublime-Squirrel.git Squirrel

on Ubuntu (other linux distors? are the paths correct?):

    cd ~/.config/sublime-text-2/Packages
    or
    cd ~/.config/sublime-text-3/Packages
    git clone https://github.com/iAmRoland/Sublime-Squirrel.git Squirrel

### File Download
Go to the downloads section and download as ZIP. 
Open up your Sublime Text packages directory and the downloaded ZIP. 
Extract the contents of the ZIP into that directory and rename Sublime-Squirrel to Squirrel.