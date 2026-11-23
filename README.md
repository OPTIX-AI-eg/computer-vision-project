This project aims to design and implement a low-cost, autonomous mobile robot capable of real-time obstacle detection and avoidance by integrating Computer Vision with Embedded Robotics. Powered by an ESP32-CAM microcontroller, the system captures live visual data from its surroundings and processes image frames to identify physical barriers and determine safe navigation paths. To ensure high reliability and rapid collision prevention, the visual processing pipeline is reinforced with an ultrasonic distance sensor (HC-SR04). Based on the fused sensor and vision data, the microcontroller dynamically drives a dual-motor chassis via an L298N motor driver to steer away from obstacles autonomously. The project demonstrates a practical, resource-efficient application of edge computer vision in robotic navigation.

Project Title: Vision-Based Autonomous Obstacle Avoidance Robot using ESP32-CAM

Microcontroller & Vision: ESP32-CAM (OV2640 Camera Module)
​Distance Sensing: Ultrasonic Sensor (HC-SR04)
​Actuation & Control: 2WD Robot Chassis, DC Gear Motors, L298N Motor Driver
​Software & Algorithms: C++ (Arduino IDE), Image Frame Processing / Edge Detection, Sensor Fusion
