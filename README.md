# CSC2002S Assignment4
# NDXSHA111

## QUESTION 1
Write a MIPS program (increase_brightness.asm) that will read in a colour PPM and increase each RGB value by 10. If the addition of 10 increases the value over 255, store the value as 255. This new image should be written to a new file. After execution display the average of all RGB values of the original file, as well the average of all RGB values of the new file, as a double value on the console

## QUESTION 2
Write a MIPS program (greyscale.asm) that will read in a colour PPM P3 image and convert this to a greyscale PPM P2 image. A greyscale pixel value is calculated by finding the average of its RGB values. Decimals are rounded down to the nearest whole number, e.g.: for a pixel with RGB values of 166, 186 and 181 respectively, the greyscale pixel value will be 177. You will need to change the file type in the header of the new greyscale file to “P2”.

## NB - Only use lf files as input images , run using QTSpim
## Sample images
- house_64_in_ascii_lf.ppm
- tree_64_in_ascii_lf.ppm
- jet_64_in_ascii_lf.ppm
  
## How to run Question 1
- Run using QTSpim and only use lf files as input images.
- Create an empty .ppm file to output the brightened image.
- Change the path of the input and output in the data section of the code to suit where your .ppm files are saved and where you have created your empty output file.
- You can now run the code using the run function on QTSpim.
- if code does not work maybe try crlf and cr images but primarily use lf.
  
## How to run Question 2
- Run using QTSpim and only use lf files as input images.
- Create an empty .ppm file to output the output greyscale image.
- Change the path of the input and output in the data section of the code to suit where your .ppm files are saved and where you have created your empty output file.
- You can now run the code using the run function on QTSpim.
- - if code does not work maybe try crlf and cr images but primarily use lf.
