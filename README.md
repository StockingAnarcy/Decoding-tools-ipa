# Decoding_tools
Tools for decoding graphic assets from .ipa files, written in python 

# Dependencies
  - [Python](http://www.python.org)
  - [Pillow (PIL fork)](https://github.com/python-pillow/Pillow)

# uncrush.py
This script is for uncrush .png from ipa

## Usage
Put the required pngs in the same folder as uncrush.py and execute

    python uncrush.py 

Note that the pngs will be overwrited

# unpack.py
Use this script to unpack .png sprites from the spritesheet packed by [TexturePacker](http://www.codeandweb.com/texturepacker/).

## Usage
Put the required .png file near a .plist or .json in the same folder as unpacker.py and execute

    python unpack.py <filename> [<format>]

### Example

    python unpack.py Sprite 
 
 or
 
    python unpack.py Sprite plist
 
 or
 
    python unpacker.py Sprite json
