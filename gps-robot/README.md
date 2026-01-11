# Automated GPS-Based Robotic Car

## Overview
This project focuses on the design and implementation of an autonomous robotic vehicle capable of navigating to predefined GPS coordinates. The system continuously recalibrates its direction using real-time GPS and compass data to maintain an accurate path toward the destination.

The project emphasizes embedded systems fundamentals such as sensor interfacing, real-time control logic, and hardware–software integration.

---

## Objective
To build a robotic car that can autonomously reach a target location using GPS data while dynamically correcting its direction without human intervention.

---

## System Description
The robotic car reads live latitude and longitude values from a GPS module and compares them with the target coordinates. A compass sensor provides heading information. Based on the deviation between the current heading and required direction, the microcontroller adjusts motor speed and direction to steer the robot toward the target.

This process runs continuously, allowing the system to correct errors caused by GPS drift or environmental disturbances.

---

## Hardware Components
- Arduino Microcontroller  
- Neo-6M GPS Module  
- Compass Module  
- Motor Driver  
- DC Motors  
- Power Supply  
- Chassis  

---

## Software Implementation
- Serial communication is used to read GPS data.
- Directional error is calculated using compass readings.
- Conditional logic determines left or right correction.
- Motor control signals are updated in real time.
- The loop continues until the robot reaches the target location.

---

## Challenges Faced
- GPS signal fluctuations affecting accuracy  
- Direction instability due to small heading changes  
- Motor overshooting during sharp turns  

---

## Solutions Implemented
- Continuous recalibration instead of one-time direction locking  
- Threshold-based heading correction  
- Gradual motor speed adjustments for smooth navigation  

---

## Results
- Successfully navigated toward predefined GPS coordinates  
- Achieved stable movement with real-time correction  
- Demonstrated reliable integration of multiple sensors  

---

## Skills Demonstrated
- Embedded C / Arduino Programming  
- GPS-Based Navigation  
- Sensor Integration  
- Motor Control  
- Real-Time Decision Logic  

---

## Future Improvements
- PID-based steering control  
- Obstacle detection using ultrasonic sensors  
- Wireless telemetry for monitoring  

---

## Author
Teja Sree Mannala
