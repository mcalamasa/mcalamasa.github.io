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



Simon, or specifically simple simon, is exactly like the famous simon game, but with two lights instead of four. My team and I used a state machine to control the different components. 
  
<img class="ui image" src="{{ site.baseurl }}/images/basys3-simon-1.jpg">
   
An 8-bit binary sqeuence is randomly generated. First, either the left or right LED flashes depending on the first number of the random sequence. Next, it is the user's turn to press the button that corresponds the light that flashed. If the user is correct, the board will flash the the first bit, then the second. Again, the user must replicate it, and so on until either the user inputs the wrong sequance or the user got to all 8 bits. Finally, the four seven segment LED's will display "Lose" or "Yeah".



Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>

