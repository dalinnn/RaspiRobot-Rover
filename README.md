#Various programs for the RaspPiRobot Rover Kit 

The kit (which includes a RasPiRobotBoard3 and an ultrasonic rangefinder) is manufactured and supplied by MonkMakes.com
https://www.monkmakes.com/pi-rover/

#1. Robot Rover controlled by a Wii Remote

This is an alternative way of controlling the Robot Rover via bluetooth and a Wii Remote. 

#2. Robot Rover and Ultrasonic Rangefinder

This python program has been developed from Simon Monk's '08_manual_robot.py' program which is included in the Rover Kit. By using multiprocessing it is possible to enable the rangefinder to be operational at the same time as the robot is being controlled by keyboard keystrokes.

Further work will to be done on this program. For one thing the program will only exit after CTRL-c is pressed twice. (Presumably because the Process loop is running at the same time?)

