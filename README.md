# Project Overview
This project presents the development of an Automatic Parking System (APS) for a toy car equipped with four DC motors, ESP32 microcontroller, and ultrasonic sensors. The system enables the car to autonomously navigate and park by leveraging sensor inputs and motor control, contributing to advancements in smart transportation.

# Key Features:
- **Four-Motor DC Control:** The car uses four motors (paired for synchronized control) managed by motor drivers to perform precise movements.
- **Ultrasonic Sensors**: Two sensors (front and rear) help detect obstacles and available parking spaces.
- **ESP32 Microcontroller:** Serves as the core controller, managing sensor inputs, decision algorithms, and motor actions.
- **Autonomous Parking Maneuvers:** The system is designed to park the car autonomously in real-time by detecting open spaces and avoiding collisions.
- **Mobile App Integration:** Users can interact with the car and initiate parking sequences via a mobile app.
# Objectives
- **Autonomous Navigation:** ESP32 controls the motors and sensors for autonomous car movement through a simulated parking lot.
- **Precision Parking:** Executes smooth parking maneuvers using synchronized motor control and ultrasonic sensor feedback.
- **Educational Value:** The project introduces users to basic robotics, autonomous navigation, and programming principles.
# Components
## Hardware:
- **ESP32 Microcontroller:** Dual-core processor with Wi-Fi and Bluetooth capabilities, used for real-time control and sensor integration.
- **DC Motors:** Used for car movement, with motor drivers providing direction and speed control.
- **Ultrasonic Sensors:** Placed at the front and rear to detect obstacles and open parking slots.
- **Servo Motor:** Rotates the front ultrasonic sensor for dynamic scanning of the surroundings.
- **Power Supply:** Four 3.7V rechargeable batteries providing a total of 12V.
## Software:
- **ESP32 Firmware:** Written in Arduino, the code controls the motors, sensors, and servo, using distance readings from the ultrasonic sensors to make parking decisions.
- **Wi-Fi Control:** Includes a Wi-Fi module that allows remote control via a mobile app or web interface.
- **HTML Control Interface:** A web-based control panel for users to control the car remotely.
# Project Workflow
- **Forward Movement:** The car moves forward until the rear ultrasonic sensor detects an obstacle.
- **Slot Detection:** The front ultrasonic sensor, mounted on a servo, rotates to detect available parking slots.
- **Parking Maneuver:** The car maneuvers into the detected parking slot based on the sensor readings.
# Future Improvements
- Adding error handling for unexpected obstacles.
- Enhancing sensor calibration for more precise parking in varied environments.
- Implementing a more robust web interface for remote control.
