# 🔐 Digital Door Lock using Arduino

This project demonstrates a secure and smart **digital door lock system** built using an **Arduino Nano**. It utilizes a **4x4 keypad** for password entry, an **LCD display** for real-time feedback, and an **SG90 servo motor** to physically lock or unlock the door. Designed for educational and prototype purposes, this system is ideal for home or office security demonstration models.

---

## 📌 Features

- Password-protected door locking system  
- Real-time LCD feedback for user interaction  
- Servo motor-based locking mechanism  
- Easy-to-build and compatible with Arduino Nano  
- Prototype built using Styrofoam for demonstration purposes  

---

## 🧰 Components Used

| Component            | Description                                         |
|---------------------|-----------------------------------------------------|
| Arduino Nano         | Main controller to process input/output            |
| 4x4 Keypad Module    | Used for entering the password                     |
| SG90 Servo Motor     | Acts as the door lock actuator                     |
| I2C 16x2 LCD         | Displays status messages to the user               |
| Breadboard           | Used to assemble the circuit without soldering     |
| Jumper Wires         | For making electrical connections                  |
| Styrofoam & Lock     | Used for building the physical demo model          |
| 5V DC Adapter        | External power supply for Arduino and components   |

---

## ⚙️ Working Principle

### 🟢 Initialization
- LCD displays: `WELCOME TO DOOR LOCK SYSTEM`
- System waits for password input

### 🔢 Password Entry
- User types in password via the keypad
- LCD shows: `Enter Password` with typed digits (or asterisks)

### ✅ Validation
- If password is correct:
  - Servo motor rotates → **Door unlocked**
- If password is incorrect:
  - Servo remains in lock position → **Access denied**

---

## 🔄 Workflow Summary

### 🔧 Arduino Setup
- Arduino Nano is programmed using Arduino IDE

### ⚡ Hardware Connections
- **Keypad** → D2 to D9  
- **Servo** → D11  
- **I2C LCD** → A4 (SDA), A5 (SCL)

### 💾 Code Upload
- Use Arduino IDE to upload the source code to the Arduino Nano

### 🧱 Enclosure Build
- Components are mounted into a Styrofoam model with a lock mechanism

---

## 📷 Connection Diagram / Model
![Image 7](https://github.com/user-attachments/assets/072534a9-74ff-406d-9724-3ca997a7243c)

---

## 🛠️ How to Build

1. Connect all components according to the circuit diagram.
2. Power up the Arduino Nano using a 5V DC adapter.
3. Upload the Arduino code using Arduino IDE.
4. Enter password via the 4x4 keypad.
5. Observe the servo motor locking/unlocking based on correctness.

---

## 📄 Project Report

A detailed project report is available in the attached PDF (`Digital-Door-Lock-Report.pdf`) which includes:

- Full component list  
- Circuit diagrams  
- Workflow and flowchart  
- Working logic  
- Results and conclusion  

---

## 📬 Authors

This project was developed by a student team as part of a **university learning activity** focused on **Arduino-based security systems**.

---
