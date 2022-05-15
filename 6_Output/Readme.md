## OUTPUT
![image](https://user-images.githubusercontent.com/102902624/168485747-5be7bcf6-9f98-402b-9f81-38dea228d650.png)

Thus, we have implemented a model that senses rains and automatically switches
on the wiper and adjusts its speed according to the intensity of the rain. As the
intensity of the rain increases, the speed of the wiper increases to a certain level. 
Figure 6 shows the workflow for our proposal. The microcontroller checks for the
digital pin and analog pin inputs of the rain sensor. When there is slight water on
the sensor, the digital pin is set to logic ’0’. This is used to detect presence of rain 
water. To check the intensity of rain, we monitor the analog pin output of the rain 
sensor, whose threshold can be adjusted manually through an attached 
Potentiometer to indicate how much water should be considered as high rain.
According to our observations, the wiper takes 2.2 seconds when a drop of water 
is poured on the sensor, while it takes only 1.4 seconds when the sensor is 
submerged in a glass of water. We learned how to interface servo motor with 
AT89C51 Microcontroller and the rain sensor module interfacing with AT89C51
Microcontroller. Figure 10 shows the prototype we have developed to 
demonstrate our idea.
