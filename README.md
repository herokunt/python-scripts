# python-scripts
A collection of several small scripts written in Python

### [Zombie Dice](https://github.com/herokunt/python-scripts/blob/main/zombiedice.py)
Zombie Dice is a "press your luck" party dice game created by Steve Jackson Games. Following along the "Automating the Boring Stuff With Python" book by Al Sweigart I wrote this script that plays this game using bots.

---
### [Conway's Game of Life](https://github.com/herokunt/python-scripts/blob/main/conway.py)
The classic Game of Life has three simple rules, but can be complex enough to build entire computational systems with it; I highly recommend to watch the first few minutes of this [great talk about The Art of Code](https://www.youtube.com/watch?v=gdSlcxxYAA8). Following along the "Automating the Boring Stuff With Python" book by Al Sweigart this is an attempt to write the game in a (hopefully) cleaner and more pythonic way.

---
### [Caesar's cipher](https://github.com/herokunt/python-scripts/blob/main/caesar-chiper.py)
One of the most popular ciphers used over 2000 years ago. Following along the "Cracking Codes With Python" book by Al Sweigart, this is an attempt to create an improved and flexible implementation of the cipher that works from the command line. It supports the expected operations of encryption, decryption as well as key derivation and brute forcing.

---
### [Transposition cipher](https://github.com/herokunt/python-scripts/blob/main/transposition-cipher.py)
A cipher that works by laying the letters of a message in a grid of varying size and encrypting the message from it. Following along the "Cracking Codes With Python" book by Al Sweigart, this is an attempt to create an improved and flexible implementation of the cipher that works from the command line. It supports the expected operations of encryption, decryption as well as key derivation and brute forcing.

---
### [Batch Resizer](https://github.com/herokunt/python-scripts/blob/main/batch-resizer.py)
Batch resizer is a small utility script that looks at a directory and processes all images in it in some way. You can resize them, convert them into other formats or bundle them together in a nice compressed archive, ready to be uploaded. Some examples: 

Resize all images to a specified width and height (aspect ratio preserved)

`$ resizer.py ~/Pictures --resize 1200 1200`

Convert all images to the specified format (jpg, png or webp)

`$ resizer.py ~/Pictures --format webp`

Add a watermark to all images:

`$ resizer.py ~/Pictures --watermark ~/logo.png`

More complex... resize images to 1200x1200 pixels, convert them to webp format,
store them in the desktop, compressed as a .tar.gz archive and delete all of the
original images afterwards

`$ resizer.py ~/Pictures -o ~/Desktop -r 1200 1200 -f webp -t -d`
