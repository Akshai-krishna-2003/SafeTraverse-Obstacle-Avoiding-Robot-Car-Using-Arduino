# 🚗 Safe Traverse: Collision‑Free Intelligent Car

> **An Arduino‑powered autonomous robot car designed to detect obstacles, make decisions in real time, and navigate safely without human intervention.**

---

## 📸 Project Preview

### 🔹 Live Prototype Image
![6c14e73f-f220-45d1-8375-544883770824](https://github.com/user-attachments/assets/6a46519e-329e-4610-8831-823bd40a01c7)




### 🎥 Working Demo (1‑Minute Video)

https://github.com/user-attachments/assets/1788673d-18e4-4bc9-a5ee-71fd96f200cd



---

## 🧠 Project Overview

**Safe Traverse** is an obstacle‑avoiding robot car developed as part of an **Embedded Systems & IoT** project. The system uses an **ultrasonic sensor mounted on a servo motor** to scan the environment and intelligently steer away from obstacles using real‑time decision logic.

The project demonstrates how **hardware + software + algorithms** combine to create an autonomous system capable of safe navigation in dynamic environments.

---

## 🎯 Key Objectives

* Build a fully autonomous robot car
* Detect obstacles in real time
* Dynamically adjust direction and speed
* Demonstrate embedded decision‑making
* Lay groundwork for future IoT & AI expansion

---

## ⚙️ Hardware Components

| Component                   | Purpose                               |
| --------------------------- | ------------------------------------- |
| Arduino Uno                 | Main controller (brain of the system) |
| Ultrasonic Sensor (HC‑SR04) | Distance & obstacle detection         |
| Servo Motor                 | Sensor scanning (left/right vision)   |
| L298N Motor Driver          | Controls motor speed & direction      |
| TT Gear Motors + Wheels     | Locomotion                            |
| 18650 Li‑ion Batteries      | Portable power supply                 |
| Jumper & Connecting Wires   | Circuit connections                   |

---

## 🧩 System Architecture

### 🔷 Block Diagram Logic

```
[Ultrasonic Sensor]
        ↓
[Servo Motor Scan]
        ↓
[Arduino Uno]
        ↓
[L298N Motor Driver]
        ↓
[Motors & Wheels]
```

---

## 🔄 Working Principle

1. Ultrasonic sensor continuously measures distance
2. If an obstacle is detected within threshold:

   * Robot stops
   * Servo scans left & right
   * Chooses safest direction
3. Motor driver adjusts speed & direction
4. Robot continues autonomous navigation

This loop runs continuously, enabling **real‑time obstacle avoidance**.

---

## 🧪 Software & Logic

* **Programming Language:** Embedded C++
* **IDE:** Arduino IDE
* **Libraries Used:**

  * `Servo.h`
  * `NewPing.h`

Motor speed, turning angle, and distance thresholds are tunable for optimization.

---

## ✅ Output

✔ Successfully avoids obstacles
✔ Smooth directional control
✔ Stable autonomous movement
✔ Real‑time environment response

---

## 🌍 Applications

* Autonomous robots
* Smart surveillance vehicles
* Warehouse automation
* Educational robotics
* Search & rescue prototypes
* Smart mobility systems

---

## 🚀 Future Enhancements

* 🔗 IoT integration (Wi‑Fi / Bluetooth)
* 🧠 AI‑based path planning
* 📺 LCD distance display
* 📡 Advanced sensors (LIDAR / IR)
* 📱 Mobile app control

---

## 👨‍💻 Author

**Akshai Krishna A**
🎓 Embedded Systems & IoT Enthusiast
📍 India

---

## ⭐ Support

If you found this project useful:

* ⭐ Star this repository
* 🍴 Fork & experiment
* 🧠 Suggest improvements

---

> *"Autonomy begins when machines learn to see, decide, and act."* 🚀
