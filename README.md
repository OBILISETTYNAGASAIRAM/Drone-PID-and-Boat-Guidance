# 🚁 Drone Altitude Control and Autonomous Boat Guidance using PID Controller

## 📌 Project Overview

This project demonstrates the implementation of a **PID (Proportional–Integral–Derivative) Controller** for autonomous systems. It focuses on maintaining stable drone altitude and guiding an autonomous boat along a predefined path under different environmental conditions.

The project also includes a **creative bonus task**, where a drone follows a **figure-eight trajectory** while compensating for wind disturbances using a controller.

---

## 🎯 Objectives

- Design and tune a PID controller for drone altitude stabilization.
- Simulate autonomous boat path tracking.
- Evaluate controller performance with and without disturbances.
- Implement a figure-eight trajectory tracking simulation.
- Visualize system behavior using Python animations.

---

## ✨ Features

- 🚁 Drone Altitude Control using PID Controller
- 🌬️ Wind disturbance simulation
- 🚤 Autonomous Boat Guidance
- 🌊 Boat guidance with and without water current disturbance
- ♾️ Figure-Eight Drone Trajectory Tracking (Bonus)
- 📊 Real-time visualization and animation
- 📈 PID tuning and performance analysis

---

## 🛠️ Technologies Used

- Python
- Google Colab
- NumPy
- Matplotlib
- IPython

---

## 📂 Project Structure

```
Drone-PID-and-Boat-Guidance/
│
├── Drone_Project.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

## ⚙️ PID Controller

The PID controller consists of three components:

- **Proportional (Kp)** – Corrects the current error.
- **Integral (Ki)** – Eliminates accumulated error over time.
- **Derivative (Kd)** – Predicts future error and improves stability.

The controller continuously minimizes the error between the desired and actual positions.

---

## 🚁 Task 1: Drone Altitude Control

The drone maintains a desired altitude even under simulated wind disturbances.

### Implemented

- PID Controller
- Gain tuning (Kp, Ki, Kd)
- Wind disturbance simulation
- Altitude response graph
- Drone animation

---

## 🚤 Task 2: Autonomous Boat Guidance

The boat follows a predefined path while compensating for water current disturbances.

### Tested Cases

- Without disturbance
- With disturbance

Controller gains were tuned to improve path tracking performance.

---

## ♾️ Creative Bonus Task

Implemented a figure-eight drone trajectory using parametric equations.

Features include:

- Figure-eight trajectory generation
- Controller-based path tracking
- Wind disturbance handling
- Smooth animation

---

## 📊 Results

The PID controller successfully:

- Maintained stable drone altitude.
- Reduced overshoot and oscillations.
- Enabled accurate boat path tracking.
- Corrected disturbances caused by wind and water currents.
- Demonstrated smooth figure-eight trajectory tracking.

---

## 🚀 Applications

- Autonomous Drones
- UAV Flight Control
- Marine Autonomous Vehicles
- Robotics
- Industrial Control Systems
- Research and Education

---

## 📸 Project Outputs

- PID Controller Response Plot
- Boat Guidance (Without Disturbance)
- Boat Guidance (With Disturbance)
- Figure-Eight Drone Tracking

---

## 📚 Learning Outcomes

This project helped in understanding:

- PID Controller Design
- Control System Fundamentals
- Feedback Control
- Autonomous Navigation
- Disturbance Rejection
- Python-based Simulation
- Data Visualization

---

## 👨‍💻 Author

**OBILISETTY NAGA SAI RAM**

Final Year B.Tech – Electronics and Communication Engineering (ECE)

---

## ⭐ If you found this project useful, consider giving it a Star!
