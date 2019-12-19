---
layout: project
type: project
image: images/basys3B.jpg
title: Simon
permalink: projects/simon
# All dates must be YYYY-MM-DD format!
date: 2019-04-12
labels:
  - Verilog
  - GitHub
  - Basys3 Board
  - Vivado Xilinx

summary: A Simon game implemented on a basys3 board.It utilizes LEDs, buttons, and a seven segment display to communicate with the player.
---
My team and I created a simplified version of the very popular Simon says game. It is simplified in the sense of only having two lights instead of four and the game only goes on until the user gets to a sequence of 8 as opposed to going on until the user loses. Also, this version doe not speed up. We used a state machine to control the different components.

<img class="ui medium right floated rounded image" src="../images/basys3-simon2.jpg">

An 8-bit binary sequence is randomly generated. First, either the left or right LED flashes depending on the first number of the random sequence. Next, it is the user's turn to press the button that corresponds the light that flashed. If the user is correct, the board will flash the the first bit, then the second. Again, the user must replicate it, and so on until either the user inputs the wrong sequence or the user got to all 8 bits. Finally, the four seven segment LED's will display "LOSE" or "YEAH".

Before this project I did have prior knowledge of Verilog, but this project made me realize that programming hardware is not the same as software. In hardware you have to store the results of components in registers and make sure the timing is right. You can't just call to a function, the components are continuously getting information and operating, so you need to extract information at the right time. I also learned that what we were doing wasn't new, meaning there were many others who faced the same problems we faced. I learned to effectively research concepts and use forums to understand and solve problems we faced. Overall, when working in an inexperienced team where each member has little to no knowledge, it is important to regularly meet up to share new found information nad help each other out. 
