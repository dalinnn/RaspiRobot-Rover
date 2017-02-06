#Various programs for the RaspPiRobot Rover Kit 

The kit (wich includes a RasPiRobotBoard3 and an ultrasonic rangefinder) is manufactured and supplied by MonkMakes.com
https://www.monkmakes.com/pi-rover/

#Robot-Rover with distance sensor

This is a python program developed from Simon Monk's '08_manual_robot.py' program which is included in the Rover Kit. By using multiprocessing it is possible to enable the rangefinder to be operational at the same time as the robot is being controlled by keyboard keystrokes.

Further work will to be done on this program. For one thing the program will only exit after CTRL-c is pressed twice. (Presumably because the Process loop is running at the same time?)

