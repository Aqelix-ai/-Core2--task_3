# URDF Workspace

This repository contains a basic ROS- workspace for an Autonomous Mobile Robot (AMR) model built using URDF (Unified Robot Description Format). It serves as a foundation for simulation and  visualization.


## Project Structure

amr_ws/
├── src/
│   ├── amr_description/
│   │   ├── urdf/
│   │   │   └── amr.urdf
│   │   ├── CMakeLists.txt
│   │   └── package.xml
│   └── .vscode/
├── README.md
└── .git/


## 🎯 Objective

The goal of this project is to:

* Build a modular AMR robot model using URDF
* Understand robot structure definition in ROS
* Prepare the robot for simulation in tools like RViz and Gazebo


## 🧩 Features

* ROS package structure (amr_description)
* URDF-based robot model
* Modular design for future expansion (sensors, wheels, links)
* Ready for simulation integration (RViz / Gazebo)


## ⚙️ Requirements

To use this workspace, you should have:

* ROS 2 : Jazzy 
* RViz2 (for visualization)
* Gazebo (optional for simulation)



## Visualizing the Robot

To visualize the URDF model in RViz:

ros2 launch urdf_tutorial display.launch.py model:=$PWD/amr.urdf



## 📌 Future Improvements

Planned upgrades include:

* Integrating sensors (LiDAR, IMU, camera)
* Gazebo simulation environment
* SLAM and navigation stack integration
* Autonomous path planning


## Learning Outcomes

Through this project, I gain practical understanding of:

* Robot modeling using URDF
* ROS 2 workspace architecture
* Simulation pipeline setup
* Modular robotics system design


📜 License

This project is open for learning and academic use.

⸻
