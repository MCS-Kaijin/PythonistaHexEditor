# Pythonista Hex Editor
A very simple hex editor for the Pythonista app. It's currently very basic and not very aesthetically pleasing, but it works.

## Functions
With this program, you can create a hex dump of a file, copy it to your clipboard, load a previously created dump, and restore a file from the presently loaded dump.

## Editing the Hex
When you load or create a hex dump, the whole dump will be displayed in a field above the three input boxes. The first box will hold the offset, which will automatically be zero, but you can navigate to any line by typing its offset which is also the first column in the field above. If you type `ADD` into the box, then a line of eight null bytes will be added to the end. Typing `POP` into the box will remove the last line. The second box will hold the bytes as hex values. You can edit any bytes, add more if there are less than eight bytes, or you can remove bytes. The last box contains the bytes as ASCII characters or a '.' if there the byte is not an ASCII character. You can edit the bytes of that line by typing a string into the box and the hex and dump will be updated accordingly.
