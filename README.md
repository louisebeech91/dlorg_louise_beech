# dlorg

a bash script for organising the Downloads folder

## what it does

dlorg will watch your Downloads folder using `inotifywait` and sort new, renamed and moved-in files into subfolders depending on the filename extension. Unknown file types will end up in *other_files*. If a subfolder is deleted or doesn't exist, the script will create the folder. 

## what you need

- Linux system - script written in bash
- inotify-tools - package provides `inotifywait`
- git - to clone the repo
- systemd - if you want to run it as a service

## setup

1. clone the repo 
 
