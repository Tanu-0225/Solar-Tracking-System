# Solar-Tracking-System
A solar tracking system is a specific device intended to move the PV modules in such a way that they continuously face the sun with the aim of maximizing the irradiation received by the PV array.

Need of solar tracking system?
1. Increase solar panel output.
2. Maximum efficency of solar panel
3. Maximum power per unit area
4. Able to gather energy throughout the day
Components Required
Arduino UNO, Servo Motor, Light Sensors, LDR, Resistors

WORKING
The primary light sensors are LDRs. Two servo motors are attached to the structure that supports the solar panel. The Arduino programme is loaded onto the microcontroller. 
The project's operation is as follows.
LDRs detect the amount of light that strikes them. There are four LDRs: top, bottom, left, and right.
In east-west tracking, the analogue values of two top LDRs and two bottom LDRs are compared, and if the top set of LDRs receives more light, the vertical servo moves in that direction.
The servo moves in the direction where the bottom LDRs receive the most light.
The analogue values from two left LDRs and two right LDRs are compared to determine the angular deflection of the solar panel.
The horizontal servo will move in the direction where the left set of LDRs receives more light than the right set.
If the appropriate set of LDRs receives more light, the servo will move in that direction.
