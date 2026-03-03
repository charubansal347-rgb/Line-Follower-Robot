# Line-Follower-Robot
Line Follower Robot Using Arduino
Objective
To design and implement an autonomous line follower robot using an Arduino microcontroller that can detect and follow a predefined path using infrared (IR) sensors.

Components Used
Arduino UNO / Nano
2 × IR Sensors
Motor Driver Module (L298N / L293D)
2 × DC Motors
Robot Chassis with Wheels
Battery / Power Supply
Jumper Wires
Working Principle
The robot uses two IR sensors to detect the contrast between a line and the background surface.
Each sensor outputs a digital signal indicating black or white surface detection.
Arduino continuously reads the sensor values and decides motor actions accordingly.
The motor driver controls the direction of the DC motors, enabling the robot to follow the line.
Control Logic
IR Sensors → Arduino → Motor Driver → DC Motors

Decision Logic Table
Left Sensor	Right Sensor	Robot Action
WHITE	WHITE	Move Forward
BLACK	WHITE	Turn Left
WHITE	BLACK	Turn Right
BLACK	BLACK	Stop
Software & Control
Programmed using Arduino IDE
Digital sensor inputs for real-time decision making
Modular motor control functions for clean logic
Delay-based motion control
Learning Outcomes
Understanding of sensor-based autonomous navigation
Interfacing IR sensors with Arduino
Motor control using driver modules
Real-time decision making in embedded systems
Limitations
Performance affected by ambient lighting conditions
No speed control (PWM not enabled)
Cannot handle sharp turns or intersections
Future Enhancements
Implement PWM-based speed control
Add PID control algorithm for smoother tracking
Use multiple sensors for better accuracy
Integrate obstacle detection
Author
Kriti Soni
B.E. Electronics & Communication Engineering
MBM University, Jodhpur
