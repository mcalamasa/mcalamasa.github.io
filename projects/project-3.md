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

<img class="ui image" src="{{ site.baseurl }}/images/cotton-header.png">

  Simon, or specifically simple simon, is exactly like the famous simon game, but with two lights instead of four. My team and I used a state machine to control the different components. 
  
  An 8-bit binary sqeuence is randomly generated. First, either the left or right LED flashes depending on the first number of the random sequence. Next, it is the user's turn to press the button that corresponds the light that flashed. If the user is correct, the board will flash the the first bit, then the second. Again, the user must replicate it, and so on until either the user inputs the wrong sequance or the user got to all 8 bits. Finally, the four seven segment LED's will display "Lose" or "Yeah".

Cotton is a horror-esque text-based adventure game I developed using the functions and macros built from The Wizard's Game in [Conrad Barski's Land of Lisp](http://landoflisp.com/). Slightly more interesting and convoluted! (It is not that scary.)

To give you a flavor of the game, here is an excerpt from one run:

<hr>

<pre>
You open your eyes, and you are greeted by an unfamiliar ceiling.
Startled, you get to your feet and quickly scan your surroundings. It's
dark except for the stream of light coming from a crack on the only boarded
window in the room. You try to peek through the crack, but you cannot see
anything. You wonder where you are and who could have possibly brought you here.

<--------------------help------------------------>
Enter quit or one of the following commands -
Weld light look walk pickup inventory help h ?
<------------------------------------------------>

look
The room is a picture of decay with only a faded number identifying it as room-4. The bed you were
 lying on is stained with what looks like dried blood. Could it be your blood? No - it is not. The
 only way out of the room aside from the door to the corridor is a window that is boarded shut. It
 looks like it has been like that for decades. There is a door going west from here. You see a candle
 on the floor. You see a match on the floor.

pickup candle
- you are now carrying the candle -

pickup match
- you are now carrying the match -

light match candle

The candle is now lit. It illuminates everything in the room.

walk west
The corridor is lit with the candle. It is so long that you cannot see to the end. You notice that
 there are words written on the wall. There is a door going east from here. There is a way going north
 from here. There is a door going south from here.
</pre>

<hr>

Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>

