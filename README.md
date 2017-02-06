#Various programs for the RaspPiRobot Rover Kit 

The kit (which includes a RasPiRobotBoard3 and an ultrasonic rangefinder) is manufactured and supplied by MonkMakes.com
https://www.monkmakes.com/pi-rover/

#01. Robot Rover and Ultrasonic Rangefinder

This python program has been developed from Simon Monk's '08_manual_robot.py' program which is included in the Rover Kit. By using multiprocessing it is possible to enable the rangefinder to be operational at the same time as the robot is being controlled by keyboard keystrokes.

Further work will to be done on this program. For one thing the program will only exit after CTRL-c is pressed twice. (Presumably because the Process loop is running at the same time?)

#02. Robot Rover controlled by a Wii Remote

This is an alternative way of controlling the Robot Rover using bluetooth and a Wii Remote.

This python program is based on Matt Hawkins' Raspberry-Pi Spy tutorial "Nintendo Wii Remote, Python and The Raspberry Pi" to be found at http://www.raspberrypi-spy.co.uk/2013/02/nintendo-wii-remote-python-and-the-raspberry-pi/ as well as Simon Monks' program above. Please note that the tutorial refers to the purchase of a USB Bluetooth dongle. This, of course, is unnecessary if you are using the newer Raspberry Pi 3 - which comes equipped with bluetooth.
