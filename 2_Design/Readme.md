## DESIGN
The project implemented here is one such project where the microcontroller based system Rain Sensing Automatic Car Wiper.

![image](https://user-images.githubusercontent.com/101176652/168485312-0a041fd5-c2d7-4210-b97a-2a649a161cd9.png)
## BLOCK DIAGRAM

![image](https://user-images.githubusercontent.com/101176652/168485365-210b612a-90c1-4e3f-9757-72d978a921db.png)
## COMPONENT DESCRIPTION
### 1. Rain Sensor Module:
A rain sensor module is an easy tool for rain detection (Gupta et al.). It can be used as a switch 
when a raindrop falls through the raining board and for measuring rainfall intensity. Figure 3 
shows a depiction of a typical Rain Sen sor Module. Due to its compact design and light 
weight, it can be easily attached into any system. The module fea tures, a rain board, and the 
control board that is separate for more convenience, a power indicator LED, and sensitivity 
adjustable through a potentiometer. A raindrop sensor is a board coated with nickel in the form 
of lines. It works on the principle of ohms law. When there is no raindrop on board. Resistance 
is high so we get high voltage according to V=IR. When raindrop present it reduces the 
resistance be cause water is a conductor of electricity and the presence of water connects 
nickel lines in parallel so reduced resistance and the reduced voltage drop across it

![image](https://user-images.githubusercontent.com/101176652/168485386-39ca960f-9337-4fa8-8f64-9203ef4ea4fc.png)
### 2. Servo Motor
Servo motors (Sachin & Gaonkar, 2013) are self-contained mechanical devices that are used 
to control the machines with great precision. Usually the servo motor is used to control the 
angular motion from 0° to 180° and 0° to 90°. The servo motor can be moved to a desired 
angular position by sending Pulse Width Modulated (Holtz, 1992) signals on the control wire. 
The servo understands the language of pulse position modulation. A pulse of width varying 
from 1 millisecond to 2 milliseconds in a repeated time frame is sent to the servo around 50 
times in a second. The width of the pulse determines the angular position. For example, a pulse 
of 1 millisecond moves the servo towards 0°, while a 2 milliseconds wide pulse would take it 
to 180°. The pulse width for in-between angular positions can be interpolated accordingly. 
Thus a pulse of width 1.5 milliseconds will shift the servo to 90°. It must be noted that these 
values are only approximations. The actual behavior of the servos differs based on their 
manufacturer. A sequence of such pulses (50 in one second) is required to be passed to the 
servo to sustain a particular angular position. When the servo receives a pulse, it can retain the 
corresponding an gular position for the next 20 milliseconds. So a pulse in every 20 
millisecond time frame must be fed to the servo. Figure 4 shows an example of the servo motor 
we have used in our implementation, while Figure 5 shows the operation of servo motor based 
on Pulse Width Modulated signals.

![image](https://user-images.githubusercontent.com/101176652/168485397-b4a7c82a-ae10-4ea8-8a33-91c8e2b687cb.png)

## FLOW CHART
![image](https://user-images.githubusercontent.com/101176652/168485421-97aa264e-ee02-4892-85bd-55d115666f76.png)
