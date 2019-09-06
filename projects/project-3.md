---
layout: project
type: project
image: images/cotton-square.png
title: Simon
permalink: projects/simon
# All dates must be YYYY-MM-DD format!
date: 2014-04-12
labels:
  - Verilog
  - GitHub
  - Basys3 Board
  
summary: A Simon game implemented on a basys3 board for EE 396.
---

My team and I created a simplified version of the very populare simon says game. It is simplified in the sense of only having two lights instead of four and the game only goes on until the user gets to a sequence of 8 as opposed to going on until the user loses. We used a state machine to control the different components. 

<img class="ui medium right floated rounded image" src="../images/basys3-simon2.jpg">
An 8-bit binary sqeuence is randomly generated. First, either the left or right LED flashes depending on the first number of the random sequence. Next, it is the user's turn to press the button that corresponds the light that flashed. If the user is correct, the board will flash the the first bit, then the second. Again, the user must replicate it, and so on until either the user inputs the wrong sequance or the user got to all 8 bits. Finally, the four seven segment LED's will display "LOSE" or "YEAH".
