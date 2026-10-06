# ROS 2 Web-Based Digital Twin & Teleoperation Dashboard


A lightweight, real-time web interface built with **HTML5, CSS3, JavaScript, and `roslibjs`**. This project connects via WebSockets (`rosbridge_server`) to a ROS 2 middleware stack to provide real-time robot state visualization, interactive map rendering, telemetry monitoring, and manual command control.

---

## 📌 Repository Context & Scope

This repository contains a generalized, standalone version of a web interface developed for an Autonomous Mobile Robot (AMR).

To adhere to university policies and academic integrity standards:
* **Backend Implementation:** The associated ROS 2 nodes, C++/Python controllers, simulation environments, and project frameworks remain in a private repository.
* **Sanitization:** All course-specific topic names, message interfaces, node identifiers, and assignment details have been replaced with standard, generic ROS 2 conventions (`/robot/*`).
* **Standalone UI Demo:** This project includes a decoupled **Demo Mode** allowing interactive evaluation of the web dashboard without requiring an active ROS 2 environment or simulation stack.
