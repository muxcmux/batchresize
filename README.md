# Batchresize - a small batch resizing utility

## Features

* Resizes all .jpg/.jpeg files from a target directory
* Creates copies to a destination directory, leaving original images intact
* Detects landscape/portrait images, so if you pass 640x480 as a size, it will figure out the portrait images and resize as 480x640
* Forks a pool of child processes to do the work for utilizing multiple processor cores

## Usage

1. Download the script to your computer
2. `$ chmod +x batchresize` to make it executable
3. `$ ./batchresize --help` to see a list of options

## LICENSE

DO WHATEVER THE FUCK YOU WANT LICENSE.