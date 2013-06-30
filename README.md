## Batchresize - a small batch resizing utility

### Features

* Resizes all .jpg/.jpeg files from a target directory.
* Creates copies to a destination directory, leaving original images intact.
* Controllable image compression to further reduce filesize (defaults to 80% of original)
* Detects landscape/portrait images, so if you pass 640x480 as a size, it will figure out the portrait images and resize as 480x640.
* Uses multiple processes to resize images concurrently (very nice if you have loads of photos and an 8-core processor).
* Copies new images while keeping original directory structure.

### Requirements

1. OSX / Linux
2. Ruby 2.0 or 1.9
3. ImageMagick lib

### Usage

Download the `batchresize` program to your computer

Download dependencies with:

    $ gem install rmagick
    $ gem install xpool

Run `$ chmod +x batchresize` to make the program executable

Run `$ ./batchresize --help` to see a list of options

Profit.

### LICENSE

DO WHATEVER THE FUCK YOU WANT LICENSE.