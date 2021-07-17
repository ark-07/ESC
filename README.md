# ESC
60A ESC 
This is our electronic speed controller design for our UAV(Unmanned Aerial Vehicle).
This PCB’s aim  when battery send a high current from 60A ,that PCB will cut highest current from 60A. 
IR2104 is a mosfet driver. We have used 3 mosfet driver because we have 3 phase for our UAV engine. Our engine’s kind is BLDC (Brushless DC).
We have used 2 mosfet for every mosfet driver like it’s datasheet data. That mosfet’s inputs can be 600V but our’s input current is between 60A and 50A max continous current for 30 seconds.

This part was our power electronic part. İn the second part of that PCB ve have used Atmega Processor because we will send PWM signal data to the IR2104. There are two mosfet for one phase. When one mosfet has been satiety position, other mosfet will be transmission position because of this we are using 2 mosfet for one phase.
 You can see Our PCB’s schematic drawings.

 

