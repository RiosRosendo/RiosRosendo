<div align="center">

# ROSENDO ADRIAN DE LOS RIOS MORENO

**Robotics & Digital Systems Engineer**

Specializing in autonomous systems, real-time embedded control, computer vision, and full-stack robotics development.

![ITESM](https://img.shields.io/badge/ITESM-Monterrey-0066cc?style=flat)
![Location](https://img.shields.io/badge/Monterrey-Mexico-0066cc?style=flat)
![Status](https://img.shields.io/badge/Status-Active-00aa00?style=flat)
![Bilingual](https://img.shields.io/badge/Languages-Spanish%20%2F%20English-0066cc?style=flat)

[Portfolio](https://riosrosendo.github.io) • [LinkedIn](https://linkedin.com/in/delosriosrosendo) • [Email](mailto:delosriosrosendo@gmail.com)

---

</div>

## PROFESSIONAL SUMMARY

Robotics and Digital Systems Engineer with expertise in designing and deploying complete autonomous systems. Experienced in bridging hardware and software across embedded systems, real-time control, and machine perception. Graduated from Tecnológico de Monterrey with demonstrated capability in full-stack robotics development, from firmware and FreeRTOS to SLAM algorithms and 3D computer vision.

**Research & Industry Experience:**
- Research Internship at AIST Japan: Advanced teleoperation systems with volumetric perception
- Industry Collaboration with John Deere: Autonomous embedded navigation systems
- Manchester Robotics: ROS2-based autonomous mobile robot control architecture

---

## TECHNICAL COMPETENCIES

### Core Robotics & Autonomous Systems
- **ROS2 / Nav2** — Distributed robotics middleware and autonomous navigation
- **SLAM Algorithms** — In-house particle filtering with CUDA optimization
- **Path Planning** — A* global planning with reactive obstacle avoidance (Bug1)
- **Inverse Kinematics** — Trajectory planning for robotic manipulators
- **Real-Time Control** — PID-based feedback systems and motor control
- **Teleoperation** — Low-latency remote operation with force feedback
- **State Machines** — YASMIN for complex mission orchestration

### Computer Vision & AI
- **Object Detection** — YOLO, ArUco markers, QR recognition
- **Pose Estimation** — MediaPipe, body tracking, hand gesture recognition
- **3D Perception** — Point clouds, ICP registration, volumetric reconstruction (TSDF/ESDF)
- **Deep Learning** — TensorFlow, model optimization for edge deployment
- **Audio Processing** — MFCC feature extraction, HMM-based voice recognition

### Embedded Systems & Hardware Integration
- **Real-Time OS** — FreeRTOS kernel design and optimization
- **Microcontrollers** — STM32, ARM Cortex, AVR architecture
- **Communication Protocols** — CAN, SPI, UART, I2C, TCP/IP
- **FPGA Design** — Verilog logic synthesis and hardware acceleration
- **Sensor Integration** — LiDAR, depth cameras, IMU, motor encoders
- **Motor Control** — Servo systems, DC motor PWM, encoder feedback

### GPU Computing & Edge AI
- **CUDA** — Parallel computing for real-time SLAM and perception
- **NVIDIA Jetson** — Inference and real-time processing on edge hardware
- **Distributed Architecture** — Coordinating Jetson edge compute with central planning

---

## PROGRAMMING LANGUAGES & FRAMEWORKS

| **Category** | **Technologies** |
|---|---|
| **Systems** | C++ (ISO 17), C (embedded), Python 3.x, MATLAB |
| **Robotics** | ROS1/ROS2, Gazebo, NVIDIA Isaac Sim, FreeRTOS |
| **Vision** | OpenCV 4.x, YOLO, MediaPipe, TensorFlow, Open3D |
| **Visualization** | Processing 4.x (Java), Three.js, Gazebo rendering |
| **Hardware** | Verilog/VHDL, Arduino SDK, STM32CubeMX, FPGA Quartus |
| **Web** | JavaScript (React, Node.js), HTML5, CSS3, SQL |
| **DevOps** | Git, Docker, Linux/POSIX, CI/CD pipelines |

---

## TECHNOLOGY STACK

### Robotics Platform
- **ROS2 Humble** — Complete robotics middleware stack
- **Gazebo Ignition Fortress** — High-fidelity robot simulation
- **NVIDIA Isaac Sim** — AI-accelerated digital twins
- **Nav2 Stack** — Navigation and autonomous control

### Perception Pipeline
- **OpenCV 4.x** — Computer vision algorithms (2D & 3D)
- **MediaPipe** — Real-time pose and hand tracking
- **YOLO v8** — Object detection and segmentation
- **Open3D** — 3D data processing and visualization
- **TensorFlow** — Neural network inference on edge devices

### Embedded & Control
- **FreeRTOS Kernel** — Preemptive real-time scheduling
- **STM32 HAL** — Microcontroller abstraction layer
- **NVIDIA CUDA Toolkit** — GPU-accelerated algorithms
- **Verilog HDL** — FPGA logic design and synthesis

### Development Environment
- **VS Code** with C++, Python, ROS extensions
- **Docker** for containerized development
- **Linux/Ubuntu** 20.04, 22.04 native development
- **Git** version control with GitHub workflow

---

## FEATURED PROJECTS

### Autonomous Forklift Robot for Warehouse Operations
**Technologies:** ROS2 • C++ • Python • SLAM • CUDA • Gazebo • State Machines

Custom autonomy stack for scaled warehouse environment (3.65m × 4.85m). Implemented in-house SLAM with particle filtering and CUDA acceleration, ArUco-based localization rescue system, A* navigation without Nav2, live digital twin in Gazebo, YASMIN state machine for pick-and-place missions, custom voice pipeline (MFCC→VQ→HMM), and FPGA-driven lifter control.

[Repository](https://github.com/JordanPalafox/SmallAutonomousMobileRobot) • [Paper](https://riosrosendo.github.io/portfolio/docs/Custom_Autonomy_Stack_for_Warehouse.pdf) • [Video](https://www.youtube.com/shorts/AEM72Lx7E6k)

### 3-DOF Robotic Arm Teleoperation via Body Pose
**Technologies:** Python • MediaPipe • Processing • ROS2 • Serial Communication

Gesture-controlled robotic arm using real-time body pose estimation. MediaPipe processes full-body keypoints to derive shoulder, elbow, and wrist angles. Hand open/close state controls gripper. Head tilt rotates the base. Achieves 85 ms end-to-end latency with <3° angular error.

[Repository](https://github.com/RiosRosendo/3dof-arm-teleoperation) • [Paper](https://riosrosendo.github.io/portfolio/docs/miniarm_3dof_teleoperation.pdf) • [Video](https://www.youtube.com/shorts/video_id)

### xArm 7 + Kinect Integration
**Technologies:** Python • OpenCV • ROS2 • xArm API • Intel RealSense

Real-time gesture recognition and depth-based object tracking for robotic arm manipulation. Integrated RGB-D perception with Intel RealSense, voxelization (TSDF/ESDF), and teleoperation interface via OpenHRC in Unity.

[Repository](https://github.com/RiosRosendo/xArm-Kinect) • [Paper](https://riosrosendo.github.io/portfolio/docs/xarm_kinect_paper.pdf)

### Autonomous Tractor Navigation System
**Technologies:** C/C++ • FreeRTOS • STM32 • CAN/UART • LiDAR • GPS

Embedded real-time firmware for autonomous agricultural robot. Developed C++ control layer on STM32 microcontrollers under FreeRTOS, integrated IMU via SPI/I2C, motor control via CAN/UART. Industry collaboration with John Deere.

[Repository](https://github.com/RiosRosendo/Tractor-FreeRTOS) • [Paper](https://riosrosendo.github.io/portfolio/docs/Autonomous_Tractor_Report.pdf)

### Additional Projects
- **Vision-Based Autonomous Patrol UAV** — OpenCV + YOLO object detection, state machine control, djitellopy SDK
- **UAV Autonomous Flight System** — ROS2 SLAM, path planning, obstacle avoidance
- **Oil Pan Tracking & Manipulation** — 3D perception pipeline (Open3D, ICP) with 6-DOF xArm
- **Smart Tractor Monitoring** — IoT sensor integration, data analytics, MATLAB processing

[View all projects →](https://riosrosendo.github.io)

---

## EDUCATION & CERTIFICATIONS

**B.Eng. in Robotics and Digital Systems Engineering**  
Tecnológico de Monterrey | Monterrey, Mexico | June 2026  
GPA: 91/100

Relevant Coursework: Advanced Embedded Systems, ROS1/ROS2, Computer Vision, Artificial Intelligence, Autonomous Systems

**TOEFL IBT English Certificate**  
Score: B2 Level (January 2025)

---

## CURRICULUM VITAE

- [CV en Español](https://riosrosendo.github.io/portfolio/docs/Rosendo_CV_ES.pdf)
- [CV in English](https://riosrosendo.github.io/portfolio/docs/Rosendo_CV_EN.pdf)

---

## CONNECT

**LinkedIn** — [delosriosrosendo](https://linkedin.com/in/delosriosrosendo)  
**GitHub** — [RiosRosendo](https://github.com/RiosRosendo)  
**Email** — delosriosrosendo@gmail.com  
**Location** — Monterrey, Nuevo León, Mexico

**Full Portfolio** — [riosrosendo.github.io](https://riosrosendo.github.io)

---

<div align="center">

Working in the present. Focused on the future.

</div>
