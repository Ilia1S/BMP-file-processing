# BMP processing
Reading and editing 24-bit BMP-file

The application does:

 1) Take three arguments as input: the name of an input file, the name of an output file and a rotation value (a number from 0 to 3).
 2) Read the input file.
 3) Print the information about the file to the console: total size in bytes, size in pixels horizontally and vertically, average image brightness.
 4) Sort the pixels in ascending order of brightness for each row.
 5) Rotate the image by the specified angle.
 6) Save the new image to the output file.
