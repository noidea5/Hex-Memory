# Hex, Memory, Images

1. What is the largest number you can store in a byte? (answer in decimal form). Jot the answer down on a piece of scratch paper.

2. How does this relate to how you describe colors in P5, Processing, or another image-based software? (talk about the answer with the person sitting next to you).

3. Use the tool [here](http://cs.ucls.uchicago.edu/~bfranke/codeDotOrg/Pixelation/Pixelation_v2.html) to encode a black and white image of your own design. Note that the first two bytes in the image bit stream represent the width and height (why are these needed?) 

4. Share the bit stream and image with your classmates. Example to the right by Noah Wong, Spring 2016 
![alt text](https://github.com/lizzybrooks/Hex-Memory/blob/master/images/aaf.png width=100 "bit stream example")
Create a Google doc called YourName_hex. Put your bit stream (0s and 1s) and your image into the file. Upload it to the Hex Projects folder in this repository.

OR- if you're feeling ambitious: 
Create a new file in the Hex Projects folder in this document. Name it YourName.md and paste your bit stream (your 0s and 1s) into the document.
Take a screen shot of your image, then use the [Markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#images) to add the image into your document. 
(Markdown is a lightweight language for styling text on the web. It's really useful on Github.)


5. Switch to the [color version](http://cs.ucls.uchicago.edu/~bfranke/codeDotOrg/Pixelation/Pixelation_v3.html). Set the “bits per pixel” to 24. In this mode, for each pixel, the first byte represents the amount of red, the second byte the amount of green, and the third byte the amount of blue. 

6. To practice, recreate a few pixels of the image below (they don’t have to exactly match the colors in the picture. Hint: for shades of gray, try making the R, G, B values similar to each other). Suggestion: use a [decimal to binary convertor](http://www.binaryhexconverter.com/decimal-to-binary-converter)!

Example:
00000011 ← width
00000001 ← height
00000000  ← amount of red
11111111  ← amount of green
11111111  ← amount of blue	
00000000
11111111
00001111
11111111
11111111
00001111


Use this base conversion Snap block to convert the following numbers from decimal to hexadecimal (jot the answers down on a piece of scratch paper):
		10
		82
		200
255
Switch to “hex mode” in the color editor. In this mode, each byte is represented by two hexadecimal digits (1 nibble, or half byte, maps to 1 hex digit). This mode matches the way colors for the web are specified! So you can use a web color picker to choose colors. Use hex mode to design a small icon for yourself. Save the bit stream under your name here.

Mapping between binary, hex, and decimal below:
binary
hex (designated by 0x)
decimal
0000 0000
0x00
0
0000 0001
0x01
1
0000 0010
0x02
2
0000 0011
0x03
3
0000 0100
0x04
4
0000 0101
0x05
5
0000 0110
0x06
6
0000 0111
0x07
7
0000 1000
0x08
8
0000 1001
0x09
9
0000 1010
0x0A
10
0000 1011
0x0B
11
0000 1100
0x0C
12
0000 1101
0x0D
13
0000 1110
0x0E
14
0000 1111
0x0F
15
0001 0000
0x10
16
...


Homework: Finish saving both of your images to the shared doc for credit.
Then, save to your shared folder two different photos that you like (not photos off the internet, but ones which you or someone you know has taken and which you have permission to use). You will be “hacking” the pixels of these images next class.
Finally, install a hex editor on your computer and open it to make sure it runs. Here’s one for Mac, Windows, Linux.
