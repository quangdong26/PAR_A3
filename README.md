# Autonomous Path Following & Obstacle Avoidance with mBot2 Neo

This repository contains the Python code and resources for the COSC3070 final project: programming an mBot2 Neo to follow a colored path, respond to traffic‑sign visuals, and avoid obstacles in real time.

## 📋 Project Overview

Autonomous robots must navigate complex environments by:
1. **Path Following**: Stay on a chosen line color (white or yellow).
2. **Sign Interpretation**:  
   - **Stop** on red sign detection  
   - **Resume** on green sign detection
3. **Obstacle Avoidance**: Detect and steer around unplanned objects using ultrasonic (or other) sensors.

A successful run requires the robot to complete the maze, obey signs, and smoothly avoid obstacles without manual intervention.

## ⚙️ Features

- Selectable path color (white/yellow)  
- Real‑time color‑based line tracking  
- Visual sign detection (red/green)  
- Ultrasonic‑sensor‑based obstacle avoidance  
- **Bonus**: LED and sound feedback on stop/go events  
- **Bonus**: Path logging & visualization via sensor data

## 🛠️ Prerequisites

- **Hardware**:  
  - mBot2 Neo robot  
  - CyberPi board & USB cable  
- **Software**:  
  - Python 3.7+  
  - Dependencies (install via `pip install -r requirements.txt`):  
    ```
    cyberpi
    mbot2
    mbuild
    opencv-python        # if used for sign detection
    numpy
    ```

## 🚀 Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your‑username/your‑repo.git
   cd your‑repo
