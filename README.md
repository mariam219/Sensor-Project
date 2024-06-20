# Sensor-Project
Our project envisions a technologically advanced road system that integrates multiple sensors
which we used to create a safer, more comfortable experience for drivers and passengers.
❖ components:
1. Soil sensor
2. 5v pump
3. Ultrasonic sensor
4. LDR (light dependent resistor)
5. eight LEDs 
6. 5v IR relay
7. Two DC motor
8. OV7670 camera module
9. Buzzer
10. Arduino uno
11. Arduino nano
12. infrared sensor (IR)
13. DHT sensor
14. LCD
15. DHT11 sensor
16. Connecting wires






➢ Detailed functionality:
For Arduino nano: -
➢ Lamp posts lighting system:
An LDR sensor is used to detect light levels. When it detects darkness, the LDRcontrolled-LEDs turn on automatically, and when light is detected, the LEDs turns off.
The setup includes connecting 4 LEDs in parallel to each other and to pin 2 of the 
Arduino. The LDR sensor is connected to analog pin “A0”.


➢ Soil sensor:
We used a capacitive soil sensor to measure the moisture in the soil, the soil was 
placed l in the middle of the road so it would be able to reduce as much as possible of 
the automobile exhaust.
The sensor output is connected to the digital pin 4.
A relay module was used to control the water pump based on the output of the 
moisture sensor. When the soil moisture is below a certain level, the relay is activated 
to turn on the water pump, ensuring the soil remains hydrated.
There was a battery connected to the relay module and the water pump.
And for the code of the soil sensor, we used:

➢ As for the ultrasonic:
An ultrasonic sensor was used to measure the velocity of the cars passing by on the 
road. This sensor detects the distance to a moving car at different time intervals. it
displays a warning on the serial monitor. The Trigger pin was connected to digital pin 
5 and for the echo pin, it was connected to pin 6 on the Arduino.


➢ traffic signal: 
A traffic signal was implemented to manage and control the flow of vehicles and to 
protect people crossing the road. The system used three LEDs (red, yellow, green). The
sequence and timing of the lights were controlled by the Arduino.
The red, yellow, green LEDs were connected to the digital pins 12,10,11 respectively.


➢ IR sensor and a buzzer:
An IR sensor was used to detect the presence of vehicles when the red light of the traffic signal 
was on. If a vehicle was detected during this time, a buzzer was activated to provide an 
audible alert, indicating that it is unsafe for passengers to cross. The IR sensor was connected 
to digital pin 7, and the buzzer was connected to digital pin 8 on the Arduino.
Additionally, power generated from wind was used to light up an LED. For this purpose, two 
DC motors were connected in series to act as generators. The rotational energy from the wind 
was converted into electrical energy by the DC motors, which was then used to power the LED.
For Arduino uno: 


➢ OV7670 camera module:
The camera module was used to capture images of vehicles passing by the road.it was 
connected to 7 digital pins and the 6 analog pins on the Arduino. The images were displayed 
on ArdulmageCapture.


➢ DHT11 temperature sensor and an LCD:
In this project, a temperature sensor is utilized to measure ambient temperature and display it 
on an LCD screen. If the temperature exceeds 27°C, a warning message is shown; otherwise, a
message wishing for a good day is displayed