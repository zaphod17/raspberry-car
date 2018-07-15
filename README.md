# raspberry-car
We write this code to check an old car radio remote using Raspberry Pi 3.
We started with a car controlled by a radio command.
The radio transmitter was removed and we replaced it with a raspberry pi 3.

The car has two engines: one is the engine of the rear wheels and controls the forward and reverse direction; the second engine control the turning of the front wheels.

To power the electric engines we use an integrated circuit call L293D: It's a quadruple high-current half-H drivers.
In the HTML page there is four arrow to control the direction of the car, and in the center of the page is present the streaming video from raspberry pi cam placed on the car.

In addition of direction control we have put a button for turn on and turn off the LED lights of the car. In particular this button is able to read the current state of the light and visualize a different icon (a bulb turned off or turned on).

Useful link:

- A javascript (jQuery) and Python (with Flask) code to control engines.
  https://circuitdigest.com/microcontroller-projects/web-controlled-raspberry-pi-surveillance-robot

- How to configure the raspberry pi cam correctly. 
  https://pimylifeup.com/raspberry-pi-webcam-server/


- L293D datasheet 
  http://www.ti.com/lit/ds/symlink/l293.pdf

