# ’Avoiding the obstacles’ game in Verilog

Wrote program in Verilog( Hardware Discription language ) and output is shown on the seven segment 
display of **Atrix-7 FPGA board**.

The player is the left most display of the seven segment display. and is denoted by a bar which can become
vertical or horizontal and can move up and down on button clicks.

The player has to avoid the obstacles coming towards it using the buttons on FPGA board.

The obstacles are the pseudo random combinations(excluded the impossible combinations like the lighing up the whole leds of display) 

Player lose when there is head on collion with the led which is at the same position as that of our player

With time the speed of incoming obstacle increase and at end the score is displayed.

![horizontal](https://user-images.githubusercontent.com/41193564/51406560-86549f00-1b7f-11e9-8ddc-92ef63d8c926.jpeg)

This shows our player as the leftmost display and other 3 contain the approching obstacles.

![vertical](https://user-images.githubusercontent.com/41193564/51406803-2a3e4a80-1b80-11e9-9113-03eb00844be0.jpeg)

This shows the player as vertical and as you can see the next obstacle contain the head on colliding led
if player doesnt move then he will lose.


![lose](https://user-images.githubusercontent.com/41193564/51406802-29a5b400-1b80-11e9-8302-0c20ac127414.jpeg)

Once lost this is displayed.

![score1](https://user-images.githubusercontent.com/41193564/51406887-68d40500-1b80-11e9-9831-83da55a3681e.jpeg)

Score is displayed at the end.

