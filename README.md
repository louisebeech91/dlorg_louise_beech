# dlorg

A bash script for organising the Downloads folder

## What it does

dlorg will watch your Downloads folder using `inotifywait` and sort new, renamed and moved-in files into subfolders depending on the filename extension. Unknown file types will end up in *other_files*. If a subfolder is deleted or doesn't exist, the script will create the folder. 

## How to use it
 
