Ascii-Art
=========

A program that turns a .jpg into an ascii art text file.  This code is meant to be saved as a function in MATLAB.  When called, the function requires three input arguments.  The first is the name of the .jpg image file in single quotes.  The second is a gamma correction value that you can play with in order to change the contrast of the resulting ascii image.  I'd recommend starting with this at 2.5 and moving up for less contrast and down for more contrast.  The third argument is the name of the output text file.  This doesn't have to exist already; the program makes it for you.  An example call to this function would look like this:

asciipic2('dan.jpg',2.2,'dan.txt');

Make sure to suppress the output with a semicolon or else you'll get tons of text in MATLAB itself.  Once it run, go to the folder where both the function and the initial .jpg are stored to find the text file.  Before opening it in notepad, I'd recommend making sure that notepad's default font is Lucida Console on size 6.  Open it up and there you go!
