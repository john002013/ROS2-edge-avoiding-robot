# ROS2-edge-avoiding-robot
A ROS2-powered edge-avoiding robot using sensor feedback and differential drive control.

📌 Overview

This project features a ROS2-powered edge-avoiding robot and its digital twin, designed to demonstrate how a robot can operate safely within a confined spatial boundary while autonomously performing its assigned tasks.

The robot uses continuous sensor feedback and ROS2 control nodes to detect table edges or drop-offs and immediately turn away, ensuring it never exits its designated workspace. The digital twin mirrors this behavior in a virtual environment, making it ideal for experimentation, safety validation, and robotic behavior testing.

# Purpose of the Digital Twin 🌟
This digital twin robot was built to demonstrate how a robot can be programmed to remain completely confined to a particular spatial region while fulfilling its duties. Such confinement:

1. Promotes Safety

Robots stay within their intended operational zone, preventing falls, collisions, and damage to surrounding objects or humans.

2. Ensures Efficiency

The robot makes real-time decisions — avoiding edges, correcting its trajectory, and continuing work autonomously without human intervention.

3. Supports a Digital Division of Labour

Multiple robots, each represented by its own digital twin, can operate in separate zones with distinct tasks.
This leads to a highly efficient robotic ecosystem where:

One robot focuses on cleaning

Another handles inspection

Another handles delivery

Each remains in its assigned digital and physical workspace

This concept demonstrates the future of specialized, cooperative robotic systems, each serving different purposes without interference.

# Features 🚀 

1. Real-time edge detection and avoidance

2. Digital twin simulation mirroring physical behavior

3. Modular ROS2 nodes for sensing, actuation, and logic

4. Autonomous differential-drive motion

5. Sensor-based safety boundary system

6. Extensible design for multi-robot simulations
   
# Tech Stack 🛠️ 

1. ROS2 Humble
2. Python or C++ nodes
3. URDF/Xacro for robot modeling
4. RViz / Gazebo / Ignition for digital twin simulation
5. Lidar Sensor
