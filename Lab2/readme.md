# Executive Summary #
In this lab you will go back to the basics. You will explore various parts of the hardware that run the code that you write, and how those devices all communicate and work with each other. You'll be introduced to the basics of how computers handle and manipulate data, and familiarize yourself with the numeric system upon which all of computing is built. And you'll be introduced to the ethics of creating technology and the importance of designing products morally. This fundamental understanding of computers will be critical to everything you do later.
***


# Hardware #


### Hard Drives and Memory ###
* Concerning a Hard Disk Drive, the term "Latency" refers to the time it takes for the information that has already been located to move in place under the head. A similar term,"Transfer Rate," refers to the capability of the hard drive itself to read and write data. The "Average Access Time" is what refers to the total time between a user request and when the requested data is available to the user.
  
* A Solid State Drive (SSD) is faster and more reliable than a Hard Disk Drive. The SSD has no moving parts, contrasting with the HDD's spinning platter and moving head. The lack of moving parts reduced the chances of hardware malfunction. To read and write data, the SSD uses a system similar to Random Access Memory, reading and writing data on memory and instantly accessing whatever the user needs when requests are made. When requesting data from an HDD, the platter needs to spin to correct position and then time the spinning with contact with the head. All this takes time, which results in slower speed for the user.
  
* The hard drive of a computer's read and write speeds are typically not fast enough to run the programs from, so the computer needs a memory bank from which to communicate back and forth at lightning speeds. Random Access Memory allows the computer to load data onto it temporarily from the hard drive to manipulate in real-time. If you use up all your RAM, data will need to be transferred back and forth from the hard drive to continue using the computer and this will create a bottleneck in the overall performance. So the more RAM a computer has installed, the faster the computer can manage many files and programs at once and continue to run smoothly.
  
* Some kinds of RAM will be able to perform faster than others. The difference between RAM that uses a 32 bit path and ones that use a 64 bit path is quite significant. 32 bit path RAM can only send out 32 bits per cycle, while the faster RAM can send out 64 bits per cycle. This increased output leads to much faster performance.
  
  
  
### ALU and the Control Unit ###

* The Arithmetic Logic Unit (ALU) serves a critical purpose in the processes of the CPU. The Control Unit, which is the main hub giving instructions to the various components around it, will send different values to be computed by the ALU. The ALU will do as instructed, like add or compare different values and then output the new value or the status of the comparison to the bus where the Control Unit will take the new output and decide the next course of action.

### CPU, Input & Output ###

* Being at the self-checkout at a grocery store is an illustration of the relationship of the input and output of the CPU. Information about the groceries being bought is collected by the scanner and converted to binary before being sent to the CPU of the machine. The data is stored on the hard drive and then processed, before being output to the screen, where the computer prompts the shoppers to input more information to pay for their groceries. This cu=yle is repeated for the payment process and the output is printed in the form of a receipt.

### Logic Gates and Circuits ###

* At the heart of computer hardware are little circuits carrying current, and to perform calculations, they use boolean logic gates. Truth tables can be quite handy to demonstrate the possible outcomes of logic gates. A truth table will list all the possible combinations of inputs for a particular gate and alongside those inputs, the outputs that will result from those combinations. For example, an NAND gate can have two or more inputs and it will always return a true outcome until all the connected inputs are true. In contrast to this, the AND gate will always return false until all its inputs are true.

# IEEE: Ethically Aligned Design #

* The IEEE is an organization focused on promoting technological innovation and for the benefit of humanity. Their contributions in this volatile field are critical to its development. Regulating the ethics surrounding the creation of new technologies keeps the users safe from being taken advantage of and their data, private.


# Data Representation #

### Numeric Conversions ###
* Decimal numbers are what we are most familiar with. The system is base 10, meaning every additional number to the left represents an increase by powers of ten. so 235 would mean two single digits, 3 10s, and 5 hundreds.


* Binary is a similar system, but it uses a base of 2, so you'll add another number to the left for every power of two. Computers typically read bytes of information which is a set of eight bits which contain binary values.


* Hexadecimal is an extension of the decimal system, expanding the base to 16. Hexadecimal uses the first 6 letters of the alphabet to represent 10-15. Because of the increased power, fewer hexadecimal numbers can represent larger quantities

### Hexadecimal Color Representation ###
* The hexadecimal color #ab00ff is close to pure violet. The six digits are split into three categories for the intensity of red, green, and blue. The red value is 171, because a, representing 10, is in the 16s place, giving it a value of 160, and the b in the 1s place adds 11, totaling 171. There is no green, represented by the 00, and the ff represents the maximum intensity for blue, equaling 255, because f, being 15, in the 16s place, equals 240, plus an additional 15 from the 1s place.

* This vivid shade of purple should be used in moderation when building web sites. Setting this as the primary color of your text on a white background might make it very difficult to read anything. You have to think about how much of it you use, the colors that complement and contrast with it, where you implement it.
***
# Conclusion #
This lab was an eye-opener. I loved learning about the physical components that computers are made up of. I found it a bit surprising how logical it all seems once the intricate parts are looked at individually. I found it satisfying to finally learn what bits and bytes are and how the binary system makes any sense. I am looking forward to the next section where we will start learning about software!
