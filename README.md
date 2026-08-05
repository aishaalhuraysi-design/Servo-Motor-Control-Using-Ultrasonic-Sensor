# 🚀 Servo Motor Control Using Ultrasonic Sensor

<p align="center">
  <img src="https://img.shields.io/badge/Arduino-Uno-00979D?style=for-the-badge&logo=arduino&logoColor=white">
  <img src="https://img.shields.io/badge/C%2B%2B-Arduino_Code-00599C?style=for-the-badge&logo=cplusplus&logoColor=white">
  <img src="https://img.shields.io/badge/Sensor-HC--SR04-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Servo-Motor-success?style=for-the-badge">
</p>

---

# 📖 Project Overview

This project demonstrates how to control a **Servo Motor** using an **HC-SR04 Ultrasonic Sensor** and an **Arduino Uno**.

The ultrasonic sensor continuously measures the distance between the sensor and nearby objects. When an object is detected within the predefined activation distance, the Arduino commands the servo motor to rotate to a specified angle. Otherwise, the servo returns to its default position.

The project also includes testing different servo angles and activation distances to observe how these parameters affect the system's response.

---

# ✨ Features

* Distance measurement using the HC-SR04 Ultrasonic Sensor.
* Automatic servo motor control.
* Adjustable servo angles (e.g., 45°, 90°, 180°).
* Adjustable activation distance (e.g., 10 cm and 15 cm).
* Real-time distance monitoring through the Serial Monitor.
* Simple and expandable Arduino implementation.

---

# 🛠 Hardware Components

| Component                 | Quantity |
| ------------------------- | -------: |
| Arduino Uno               |        1 |
| HC-SR04 Ultrasonic Sensor |        1 |
| Servo Motor               |        1 |
| Breadboard                |        1 |
| Jumper Wires              |  Several |

---

# 🔌 Circuit Connections

## Servo Motor

| Servo Wire | Arduino Pin |
| ---------- | ----------- |
| Signal     | D9          |
| VCC        | 5V          |
| GND        | GND         |

## HC-SR04 Ultrasonic Sensor

| Sensor Pin | Arduino Pin |
| ---------- | ----------- |
| Trig       | D10         |
| Echo       | D11         |
| VCC        | 5V          |
| GND        | GND         |

---

# 📷 Circuit Setup

<img width="720" height="1280" alt="circuit_setup" src="https://github.com/user-attachments/assets/354c22e0-25ab-45ab-9dc4-51a76085081f" />


```markdown
![Circuit Setup](images/circuit_setup.jpg)
```

---

# 🧪 Experiments

## Experiment 1 – Servo Angle = 90°

**Objective**

Observe the servo motor movement when an object is detected within **10 cm**.

**Observation**

* The ultrasonic sensor successfully detected nearby objects.
* The servo motor rotated smoothly to **90°**.
* When the object moved away, the servo returned to its initial position.

🎥 **Demo Video**

```text
videos/servo_90_degree.mp4

https://github.com/user-attachments/assets/adfef9a7-f687-4bf9-923c-62affb943e03


```

---

## Experiment 2 – Servo Angle = 180°

**Objective**

Evaluate the effect of increasing the servo rotation angle.

**Observation**

* The servo rotated to **180°** when the object was detected.
* Increasing the angle expanded the servo's movement range.
* The sensor continued detecting objects accurately.

🎥 **Demo Video**

```text
videos/servo_180_degree.mp4



https://github.com/user-attachments/assets/985ce1de-cd1e-4c47-8c2c-3d160dfdaea2



---

# 📊 Results

The project successfully demonstrated:

* Accurate distance measurement using the HC-SR04 sensor.
* Reliable servo motor control based on object distance.
* Successful testing of multiple servo angles.
* Successful modification of the activation distance.
* Stable system performance during all experiments.


---

# ▶️ How to Run

1. Connect the circuit as shown above.
2. Open the Arduino sketch.
3. Select **Arduino Uno** from the **Boards** menu.
4. Select the correct COM port.
5. Upload the code.
6. Open the Serial Monitor (9600 baud).
7. Move an object toward the ultrasonic sensor and observe the servo response.

---

# 👩‍💻 Author

**Aisha Alhuraysi**

IT Graduate | Artificial Intelligence & Robotics Training

Smart Methods Internship




