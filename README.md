# Path Finder
An Arduino based robot that follows a path, identifies obstacles and changes its direction accordingly.

The algorithm used is the one that first detects the obstacle, and if any obstacle found, the robot will find a better alternative and change it's path.

# Team Members:

1. Karuna Varshney
2. Nitish Chauhan
3. Rohit Motwani
4. Saurabh Sagar

# Hardware Used:

- Arduino Uno Board
- Motor Shield L293D
- Ultrasonic Sensor
- Mini Servo Motor
- DC Motor and Wheel x4
- Chassis 4WD
- Bracket for HC-SR04
- Battery 9V x2
- Battery Buckle x2
- Wires
- Button
- Glue Gun

# Software Used:

- Arduino Software(IDE).
- Library for motor driver module (Adafruit AF_Motor Arduino library).
- The NewPing Arduino Library.
- Adobe Photoshop.
- A Windows OS – Windows 7 or above or A Mac OSX - 10.11 or above.

# Connections:

C) Connections :

1) DC Motors connect to the Motor Shield
2) Left Motors connect to M1 and M2 (If the motors run backwards, change the (+) and (-) connections)
3) Right Motors connect to M4 and M3
4) The Servo motor connect to the Motor Shield

- The Servo1 input is connected to the Arduino Digital10 input
- The Servo2 input is connected to the Arduino Digital9 input

5) The HC-SR04 Sensor connections

- The HC-SR04 Sensor VCC connect to the Arduino +5V
- The HC-SR04 Sensor GND connect to the Arduino Ground
- The HC-SR04 Sensor Trig connect to the Arduino Analog 0
- The HC-SR04 Sensor Echo connect to the Arduino Analog 1

6) Battery and on / off button connection

- The (+) from the battery is connect to a leg of the button
- Connect a cable to the other legs of the button. This cable is for Motor Shield (+)

7) 2 seperate DC power supplies for the Arduino and motors

- If you would like to have 2 seperate DC power supplies for the Arduino and motors. Plug in the supply for the Arduino into the DC jack, and connect the motor supply to the PWR_EXT block. Make sure the jumper is removed from the motor shield.

8) Attach the wheels
