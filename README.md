# Arduino-Radar
📌 Overview

The Arduino Radar project demonstrates a radar system prototype based on an Arduino board that detects both stationary and moving objects. Using an ultrasonic sensor mounted on a servo motor, the system scans its surroundings and displays detected objects on a radar-like graphical interface.

🎯 Aim

To design and implement a radar system prototype that detects objects using an ultrasonic sensor and visualizes them on a Processing IDE radar display.

🛠️ Components Used

Ultrasonic Sensor – For distance measurement

Servo Motor – For angular scanning (0°–180° rotation)

Arduino Uno – Microcontroller board

Breadboard – For circuit prototyping

Jumper Wires – For connections

⚙️ Working Principle

The ultrasonic sensor transmits sound waves and detects reflections from nearby objects.

The servo motor rotates the sensor across angles, enabling scanning of a defined area.

Arduino Uno collects sensor data and transmits it to a PC via serial communication.

Processing IDE visualizes the data in a radar-style graphical interface.

📐 Ultrasonic Sensor Operation

The distance to an object is calculated using:

𝐷
=
1
2
×
𝑇
×
𝐶
D=
2
1
	​

×T×C

Where:

𝐷
D = Distance (meters)

𝑇
T = Time taken (seconds)

𝐶
C = Speed of sound (343 m/s)

🔧 Hardware Setup

Ultrasonic sensor mounted on servo motor

Connected to Arduino Uno through breadboard & jumper wires

Arduino connected to PC via USB

💻 Software Requirements

Arduino IDE (1.8.13 or later) – For coding & uploading Arduino sketch

Processing IDE – For radar-style graphical visualization

🖥️ Implementation Steps

Assemble components on breadboard.

Connect ultrasonic sensor and servo motor to Arduino Uno.

Upload Arduino sketch using Arduino IDE.

Open Processing IDE, paste radar visualization code, and update COM port.

Run Processing code → radar interface opens.

Objects detected within sensor range are displayed graphically.

📊 Output

Servo motor sweeps ultrasonic sensor from 0° to 180°.

Detected objects are plotted in real-time on a radar-like display.

Provides a clear visualization of object presence and distance.



🚀 Applications

Obstacle detection in robotics

Security and surveillance systems

Collision avoidance in autonomous systems

Educational demonstrations of radar principles
