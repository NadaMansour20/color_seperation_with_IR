<h1>A Simple explanation of the project </h1>
- simple arduino project used ir_sensor to  2 colors separatio (white and black).

<h1> Tools</h1>
*Arduino Uno
*Bread Board
*Servo_Motor
*IR_Sensor
*Ultrasonic_Sensor
*Leds


<h1> Hardware Connection </h1>

![Screenshot 2024-03-01 165910](https://github.com/NadaMansour20/color_seperation_with_IR/assets/125664031/36c2ac13-fc9e-4621-a8a0-b6a2fda9766b)

<h1>Code</h1>
* IR_Sensor is used to detect objects and determine the color white or black
*The initial angle of the Servo_Motor is 90, when IR_sensor detect white object the white led turn on and the angle move to 0 --> righ
and when IR_sensor detect black object the blue led (instead of black led) turn on the angle move to 180 --> left
*Ultrasonic_Sensor used to detect object 20 away to turn IR_Sensor and Servo




