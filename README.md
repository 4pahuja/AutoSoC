# Project Proposal - Arnav Pahuja

This project aims to make a simple SoC that combines the Microwatt core and specialized acceleration circuitry suited for Autonomous vehicles or Robotics platforms. Specifically, accelerating these workloads, in this order:

- LiDAR data processing
- Camera data processing
- Sensor Fusion

Combining the hardware acceleration, with support for running a simple ROS (Robot Operating System) node on the core, to communicate with other systems. This will require either implementing custom firmware or getting ROS working through Linux/MicroPython which will be the harder way. For communication, a simple goal can be to test and use `rosserial` using UART.

The performance can be measured by benchmarking the system using common algorithms and observing the speedup:

- SLAM
- Visual SLAM
- Object Detection
- Kalman Filters

While I have partial exposure to all these domains, it will be a great learning opportunity for me how much ever I accomplish. Thank you for this opportunity.

Some associated tasks that this may involve may be getting particular sensor firmware to work on the core.
