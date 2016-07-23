## Iconify

Generate [icns](https://en.wikipedia.org/wiki/Apple_Icon_Image_format) from a single 1024x1024 png.

### Installation

* clone or download this repo
* add `export PATH="$PATH:path/to/this/repo"` to `~/.bash_profile`
* `source ~/.bash_profile`

### Usage

`iconify <path/to/image.png> <path/to/destination>`

example:

`iconify ~/Desktop/sick-icon.png ~/Desktop/`

will generate an icns file on your desktop with the following sizes:

* 16x16
* 16x16@2x
* 32x32
* 32x32@2x
* 128x128
* 128x128@2x
* 256x256
* 256x256@2x
* 512x512
