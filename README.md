# Smart Arduino Car Using Ultrasonic Sensor

## Overview
This project demonstrates an **autonomous car** built using **Arduino** and an **ultrasonic sensor**. The car is capable of detecting obstacles in its path and intelligently navigating around them by determining the optimal direction to move. It was designed to provide a simple yet effective solution for obstacle avoidance using basic components like motors, sensors, and servos.

## Features
- **Autonomous Movement**: The car moves forward until it detects an obstacle, then calculates the best direction to continue based on distance measurements.
- **Ultrasonic Obstacle Detection**: A servo-mounted ultrasonic sensor scans both left and right to determine obstacle proximity.
- **Real-time Decision Making**: The car adjusts its path in real-time, ensuring smooth navigation in a dynamic environment.
- **Arduino-controlled Motors**: The project makes use of Arduino to control the motors, servo, and sensor logic.

## How It Works
1. The car moves forward until it detects an obstacle within a range of 15 cm.
2. Upon detecting an obstacle, the ultrasonic sensor scans both left and right to check which direction is safer to move.
3. Based on the scan, the car turns in the direction with more space and continues moving forward.

## Key Components
- **Ultrasonic Sensor**: Detects the distance to obstacles.
- **Servo Motor**: Rotates the sensor to scan for obstacles on the left and right.
- **Motors**: Four motors drive the car's wheels for forward and backward movement.
- **Arduino**: Controls the decision-making process and motor operations.

## Challenges Faced
- **Weight Distribution**: Balancing the weight of the car for smooth movement and stability during turns.
- **Torque**: Ensuring that the motors provide enough power to move the car efficiently.
- **Traction**: Selecting appropriate wheels to provide sufficient grip on different surfaces.

## Future Improvements
- Implementing more sensors for enhanced obstacle detection.
- Adding Bluetooth or GPS modules for remote control or navigation.
- Improving the algorithm for better decision-making in more complex environments.

## How to Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-repo-link/smart-arduino-car.git
   ```
2. **Upload the code**:
   Open the Arduino IDE, connect your Arduino, and upload the code from the repository.
3. **Power the car**: Connect the power supply and watch the car navigate autonomously.

## Conclusion
This project offers a hands-on introduction to building autonomous systems using Arduino and basic components. The **Smart Arduino Car** demonstrates how to combine sensors, motors, and control logic for effective obstacle avoidance, providing a strong foundation for further exploration in robotics and automation.
