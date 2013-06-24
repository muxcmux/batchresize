## Batchresize - a small batch resizing utility

### Features

* Resizes all .jpg/.jpeg files from a target directory.
* Creates copies to a destination directory, leaving original images intact.
* Detects landscape/portrait images, so if you pass 640x480 as a size, it will figure out the portrait images and resize as 480x640.
* Uses multiple processes to resize images concurrently (very nice if you have loads of photos and an 8-core processor).
* Copies new images while keeping original directory structure.

### Requirements

1. OSX / Linux
2. Ruby 2.0 or 1.9
3. ImageMagick lib

### Usage

1. Download the `batchresize` program to your computer
2. Download dependencies with:
    
      $ gem install rmagick
      $ gem isntall xpool
    
3. Run `$ chmod +x batchresize` to make the program executable
4. Run `$ ./batchresize --help` to see a list of options
5. Profit.

### LICENSE

DO WHATEVER THE FUCK YOU WANT LICENSE.