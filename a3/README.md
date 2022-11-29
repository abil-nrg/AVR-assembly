###ASSIGNMENT 3
<!--
-->
-Used mulitiple AVR 16-bit timers
-Used interupts
-Interacted with the lcd display
-Interacted with input devices

##How to USE
-Acquire an ATMEGA 2560 microchip, Buttons, and an lcd screen
-Load the files into micochip studio and build them
-Export the built files onto the microchip
-Have fun

#part a
-Changed the display on the lcd display depending on whether or not a button has been pressed
-Read the value in the ADC, depending on the range changed the value of a variable

#part b
-Depending on the range of the ADC, updated which button was pressed
-Depending on what button was pressed, a specific letter was written to the lcd

#part c
-We are able to scroll through a charset in the top line of the lcd
-Scrolling up when pressing the UP button
-Scrolling down when pressing the DOWN button
-Reaching the boundry of the charset left us on the same letter

#part d
-Implemented the ability to change where in the top line of the lcd we are
-Can change the letter in any part of the lcd displays top line
-Storing previous values and able to change them at any time

