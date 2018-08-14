# EdubotSoftware

Provides modular, flexible code for use with EduBOT, the educational robot developed by LAROSE-UFRGS. 

## LibMotor 
Motor interface through an H-Bridge, intended to control the robot's wheels. Also uses the Encoder library to measure angular velocity of the wheel.
## LibSonar
Provides a simple interface with Ultrassound distance sensors. 
## Controller
Implements a PID controller. Used by EduLib to control motor velocity.
## EduLib
Uses LibMotor, LibSonar, and Controller to provide a simple interface for students to control the robot. 
The design philosophy for EduLib is to abstract more complex control issues, so that students only need to design a logical algorithm. 
For example, rotating the robot by 90 degrees is as easy as "edu_rotaciona(90);"
