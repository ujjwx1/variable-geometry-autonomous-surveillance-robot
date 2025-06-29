# 🤖 Variable Geometry Autonomous Surveillance Robot – for Defence Purposes  t  
**Author**: Ujjwal Aggarwal  
**Institution**: Thapar Institute of Engineering and Technology  
**Design Year**: 2024  
**Published**: 2025  

---

## 🎬 Project Demo Video

<p align="center">
  <a href="https://drive.google.com/file/d/1ftz_JRLJ6LhsW8qkGFzek8BeCZi9EWui/view" target="_blank">
    <img src="images/video_thumbnail.jpg" width="70%" alt="Watch the Project Video"/>
  </a>
</p>

<p align="center">
  <strong><a href="https://drive.google.com/file/d/1ftz_JRLJ6LhsW8qkGFzek8BeCZi9EWui/view">🎥 Click here to watch the full project walkthrough</a></strong>
</p>

---

## 🧭 Project Objective

Design and prototype a modular, military-grade autonomous surveillance robot optimized for rugged terrain. The robot is capable of navigating uneven surfaces, climbing steep inclines, and carrying payloads like cameras or communication modules.

---

## 🔄 Design Evolution

### 🔹 Version 1 – Tracked Rocker-Bogie
- **Inspiration**: NASA Mars Rover
- **Mechanism**: Rocker-bogie suspension with continuous tracks
- **Goal**: Passive obstacle traversal and terrain adaptability
- ![](images/cad/v1.png)

---

### 🔹 Version 2 – Triangular Tank Climber
- **Inspiration**: Triangular tank-style tracked base
- **Mechanism**: Compact, incline-optimized geometry
- **Goal**: Wall climbing and slope traversal
- ![](images/cad/v2.png)

---

### 🔹 Version 3 – Hybrid (Packbot-Inspired)
- **Inspiration**: iRobot PackBot military robot
- **Mechanism**: Triangular tracks + articulated rocker joints
- **Goal**: Combine climbing ability with articulation for extreme terrain
- ![](images/cad/v3.png)

---

## 🛠️ CAD & PCB Design

### 🧱 CAD Models
- Created using [Fusion 360 / SolidWorks / CATIA — choose your tool]
- Detailed assemblies and subcomponents for all three versions
- Modular design allowing multiple physical configurations

### 🔌 PCB Design
- Custom motor controller PCB designed in KiCAD
- Microcontroller: ESP32
- Motor Driver: DRV8833 dual H-bridge
- Power: 3S LiPo regulated via buck converter
- ![](images/pcb_layout.png)

---

## 📸 Build Gallery

| Frame Assembly                  | Initial Electronics Setup         | Outdoor Field Test                |
|--------------------------------|-----------------------------------|-----------------------------------|
| ![](images/builds/frame.jpg)   | ![](images/builds/test.jpg)       | ![](images/builds/outdoor.jpg)    |

> Includes full-frame photos, wiring test, and live environment trials.

---

## 💡 Inspirations

- **iRobot PackBot** – Military robot used by U.S. Army
- **NASA Rocker-Bogie Rovers** – Proven mobility system for uneven terrain
- **Modern Tracked Tanks** – Triangular tread designs for incline mobility

---

## 🗂️ Repository Structure

