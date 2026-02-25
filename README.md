# autonomous-self-driving-car ( video prototype )
https://drive.google.com/file/d/1YrossdPn-wok7D5Pf-ieYA4mGVcgtPoc/view?usp=drivesdk&usp=embed_facebook&usp=embed_facebook

# 🚗 Autonomous Self-Driving Car

A simple self-driving car project implemented in **C++ and Arduino**, designed to demonstrate basic autonomous navigation using sensors and computer vision techniques. This project showcases fundamental concepts in robotics, obstacle detection, and motion control.

---

## 🧠 Project Overview

This repository includes:
- **Arduino code** to control a physical RC/robot car using sensors.
- **OpenCV C++ code** for basic visual processing (e.g., lane tracking or object recognition).
- A **Capstone Project PDF** with detailed documentation explaining the system design and implementation. :contentReference[oaicite:2]{index=2}

The goal is to give you a starting point for autonomous vehicle experimentation — whether on a real robot or as a learning prototype.

---

## 📦 Contents

| File | Description |
|------|-------------|
| `arduino code.ino` | Arduino sketch to read sensors and control motors. :contentReference[oaicite:3]{index=3} |
| `openCV code.cpp` | C++ code using OpenCV for visual processing tasks. :contentReference[oaicite:4]{index=4} |
| `Capston Project.pdf` | Project documentation with explanation and diagrams. :contentReference[oaicite:5]{index=5} |

---

## 🛠️ Technologies & Tools

This project uses the following:

✔ **C++** — Core algorithms for image processing and control  
✔ **Arduino** — Microcontroller for sensor input and motor outputs  
✔ **OpenCV** — Computer vision library for processing camera input  
✔ **Sensors** — Environmental perception (distance, object detection) :contentReference[oaicite:6]{index=6}

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Bbzz98/autonomous-self-driving-car.git
cd autonomous-self-driving-car

2. Arduino Setup

Open arduino code.ino in the Arduino IDE.

Connect your Arduino board (e.g., Uno, Nano).

Connect sensors & motors according to your hardware setup.

Upload the sketch to your Arduino.

3. OpenCV Vision Processor

Install OpenCV for C++ (e.g., using vcpkg or system package manager).

Compile the openCV code.cpp file:

g++ openCV\ code.cpp -o vision `pkg-config --cflags --libs opencv4`

Run the vision module (e.g., for lane or obstacle detection)

Usage & Examples

This project does not include a ready-made simulator, so you’ll need:

A test environment or robot hardware

A camera or sensor setup

Basic control experimentation

Typical flows:
✔ Detect obstacles → react (stop/turn/avoid)
✔ Track a line or path using vision input
✔ Combine sensor & vision data for autonomous motion

📄 Documentation

See Capston Project.pdf for:

System architecture

Sensor wiring diagrams

Control logic explanation

Results and conclusions

This makes it easier to understand the ideas and design choices behind the code.

📌 Future Improvements

Here are some ways you could expand this project:

Integrate PID controllers for smoother steering

Add lane detection with better accuracy

Use deep learning (neural nets) for more complex perception

Integrate ROS (Robot Operating System) for modular controls

License

This repository currently has no formal license — consider adding one like MIT to allow others to reuse and improve your work.

🚀 Final Notes

This project is a great hands-on start for anyone interested in robotics, embedded systems, or autonomous systems! Keep developing and experimenting.

Happy coding! 🤖✨


---

### If you want, I can also:

✔ Add badges (build/status, issues, license)  
✔ Add screenshots or GIFs  
✔ Improve the PDF content for clarity  

Just tell me what you want next!
::contentReference[oaicite:8]{index=8}
