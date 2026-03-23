# Franka Vision Teleop

This project enables teleoperation of a Franka Panda robot arm using computer vision and machine learning. It explores intuitive, vision-based control methods to manipulate the arm in real-time, bridging perception and action for robotic manipulation tasks.

## Key Features
- Real-time hand pose estimation for teleoperation control
- Low-latency communication with the Franka Panda via libfranka
- Coordinate mapping from camera space to robot workspace
- Safety-conscious velocity control for smooth movement

## Tech Stack
- Python, OpenCV, MediaPipe
- C++ (libfranka), ROS 2 (optional)
- Camera (Intel RealSense / webcam)

## Getting Started
```bash
git clone https://github.com/zoreanuj/franka-vision-teleop.git
cd franka-vision-teleop
pip install -r requirements.txt
# Configure your Franka's IP and run:
python src/teleop_main.py
```