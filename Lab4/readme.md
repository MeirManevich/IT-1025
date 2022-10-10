# Executive Summary #
In this unit you will program your first program! You will explore the basics of Python programming, and by doing so, be exposed to some of the fundamental ideas of programming, like variables, strings, and functions. You’ll also get to create your own logo and learn about different images and file types and which ones are useful for software development.
***
# Python IDLE #

* There are a couple of ways to go about programming in Python. Using the shell program or text editor will both allow you to run Python programs, but in different ways. 
	* The shell editor executes each line you write, as you write it. This is very useful for tinkering around and trying out new lines of code on the fly. 
  * But for writing a longer program, a text editor is more useful, because it doesn't try to execute any of the lines you write. You can write for as long as you want to, and when you are done, if you save the file with the .py extension, you will be able to run the code as a program by opening it with python. 
  * The key way to differentiate between the shell and a text editor is that the shell always has a ‘>>>’ before each line, whereas a text editor does not.

### Code Examples  ###
* Variables are containers of information, representing whatever is assigned to them, quite like variables in math. For example, “variableTest = 7” means that “variableTest” is now a container for the number 7. Guido van Rossum, the creator of Python, infused his language with a Monty Python theme because he was reading scripts for “Monty Python’s Flying Circus” at the time he was creating Python. Silly variables such as “spam,” “bacon,” and “eggs” are common exemplary variables, inspired by the Monty Python skit called, “Spam.” 

* An assignment statement is what gives a variable its value. In Python, the = operator is used to denote assignment. So “variableTest = 7” doesn't read “variableTest is equal to 7” but rather “variableTest now holds the value of 7.”

* A function is a command that Python will execute. For example the “print()” function will make the computer type whatever is contained in the argument of the function, contained in the parentheses.
* Three data types:
  * Integer: Integers, written as “int” in Python are all non-decimal numbers
  * Floating-point: Floating-point numbers, written as “float” in Python, are all the numbers with decimals.
  * String: Strings, writing as “str” in Python, are sequences of text. Enclose any text you want as a string in quotations to let Python know you want to make a string, even if it has numbers in it.

# Graphics #
 
### Raster vs. Vector Graphics ###
* Raster images are comprised of many tiny pixels, that, when viewed zoomed out to a specific size, create a sharp image with little evidence to the pixels. But if you zoom in to a raster image too much, each individual pixel will become visible and the image will look pixelated and be unpleasant to look at.
* Vector graphics solve the zoom-pixelation issue by not using pixels at all. Vector images are more advanced graphics that are based on rules of geometry that stay consistent regardless of how zoomed in the image is. This produces a sharp viewing experience no matter what context the image is used in.
 
### Lossless vs. Lossy Compression ###
* Lossless Compression stores images in such a way that all of the original data is preserved exactly the way it was when uncompressed. Using lossless compression can create large file sizes and be unnecessary in many cases. When developing a program or website that relies on images, using lossless compression is probably going to slow down everything because of the time it will take to load the images. Finding a lossy compression algorithm that suits your needs will speed up your program and ensure an efficient experience.
* Lossy Compression stores images at smaller sizes by intelligently analyzing the image data and removing parts that don’t affect the overall image very much, like removing color data for colors that are barely used in the image. Lossy compression, when done correctly, can produce identical-looking images at much smaller file sizes. Good file compression can enhance a program or website for developers by providing them with the perceived quality they desire while giving the program very little file sizes to deal with.
 
### File Formats ###
* JPEG is probably one of the most widely used image file formats. It uses lossy compression to store the images at a smaller size, but it provides control over how much the image is compressed
* GIF is a lossless file format that allows only 8 bits per pixel, so the color range is less than other formats, like JPEG and PNG. It does allow animated images, which makes it unique among the many file formats.
* PNG is also a lossless file format, but it allows up to 48 bits per pixel, allowing much higher detail. And in addition to that, it supports transparency, which allows seamless integration of graphics in websites and programs, making ugly borders invisible.
 
### File Properties ###
* The logo I designed reflected my appreciation for simplicity and leading lines. I used four layers, which consisted of the two intersecting triangles, a yellow rectangle to fill in background space, and a lock. The lock is positioned at the intersection of the triangular lines, drawing your eye to it immediately. And I used complementary soft colors in the blue/purple and yellow range to make it pleasing to look at.
* Upon opening up the properties of my logo, I can see it is a mere 5.08 kilobytes, and it opens with Google Chrome by default. While it does open in Chrome in a new tab, I think it would be more appropriate to open it as an image with my computer’s default image program. Unfortunately the default Windows app for images doesn’t support svg files natively and I don’t have any other program installed that can view svg files, so I’ll have to stick with Chrome for now.

***
# Conclusion #

This unit was great fun! I have already begun learning Python on my own so I was eager to work on this topic. And I thought the graphics section was really interesting, especially creating my own logo! I wasn’t aware of websites like that which make it so easy to get started. Anyway,  I will continue to learn and practice programming in Python on my own, and I hope to make a career out of this one day. I really do love it.


