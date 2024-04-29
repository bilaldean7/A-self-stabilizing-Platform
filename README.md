
## Project Overview
This repository hosts the complete codebase and documentation for the "A Self-Stabilizing Platform" project, my Bachelor's thesis at Metropolia University of Applied Sciences. The goal of this project was to design and implement a DIY self-stabilizing platform leveraging the principles of gyroscopic stabilization with micro-electromechanical systems (MEMS).

## Technical Description
The platform utilizes an MPU6050 sensor module which integrates both a gyroscope and an accelerometer. This sensor helps in maintaining the platform's stability by constantly adjusting its position to counteract any tilting movements. The system is controlled through an Arduino UNO, interfacing with the MPU6050 via the I2C protocol. Servo motors are employed to physically adjust the platform, achieving real-time stabilization.

## Key Features
- **Self-Stabilization:** The core feature, allowing the platform to maintain a horizontal orientation regardless of external disturbances.
- **MEMS Technology:** Utilizes the MPU6050 module for precise motion tracking and position adjustments.
- **DIY Implementation:** All components used are readily available and the system can be assembled with basic technical skills.

## Development Process
The development process included hardware assembly, software programming, and iterative testing. The project highlights the practical application of theoretical electronics and control systems principles in creating a functional self-stabilizing mechanism.

## Usage Scenarios
This platform can be adapted for various applications such as camera stabilization for amateur photography or videography, enhancing the quality of footage captured through dynamic movements.

## Future Enhancements
Future work could explore the integration of more robust servo motors and the incorporation of smoother materials for the platform's housing to enhance performance and durability.

## Contributions and Acknowledgments
This project was supervised by Anssi Ikonen, Senior Lecturer at Metropolia UAS. Contributions to the codebase and design improvements are welcome and appreciated.

## License
The project is open-sourced under the MIT License. Feel free to fork, modify, and use it in your projects with appropriate attribution.


