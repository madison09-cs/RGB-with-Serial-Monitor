# 🎛️ RGB with Serial Monitor

A simple yet powerful Arduino project that allows you to control an RGB LED using the **Serial Monitor**. Adjust color intensity and toggle the LED on/off in real-time by sending commands directly from your computer.

---

## 📝 Description

**RGB with Serial Monitor** is an interactive Arduino project where users can control the red, green, and blue components of an RGB LED using the Serial Monitor in the Arduino IDE. It demonstrates how serial communication can be used to interact with hardware in real-time — adjusting colors, brightness, and turning the LED on or off with simple commands.

This project is ideal for learning how to use **serial input**, **PWM (pulse width modulation)**, and **basic RGB color mixing**.

---

## 🔧 Components Used

| Component               | Quantity |
|-------------------------|----------|
| Arduino Uno R3          | 1        |
| RGB LED (Common Cathode)| 1        |
| 220Ω Resistors          | 3        |
| Breadboard              | 1        |
| Jumper Wires / Cables   | Several  |
| USB Cable (for Arduino IDE) | 1     |

---

## 🚀 Installation & Setup

1. **Circuit Setup**:
   - Red pin of RGB LED → Digital Pin 9 (with 220Ω resistor)
   - Green pin → Digital Pin 10 (with 220Ω resistor)
   - Blue pin → Digital Pin 11 (with 220Ω resistor)
   - Common Cathode → GND

2. **Upload Code**:
   - Connect your Arduino Uno to your PC using a USB cable.
   - Open the Arduino IDE.
   - Select the correct **board** and **COM port**.
   - Upload the provided sketch to your board.

3. **Open Serial Monitor**:
   - Set baud rate to **9600**.
   - Type commands to control the LED (e.g., `255,0,0` for red).

---

## ⚙️ How It Works

- The **Serial Monitor** receives input in the form of 3 comma-separated values (R, G, B).
- These values (0–255) set the brightness of each color channel via **PWM**.
- For example:
  - `255,0,0` → Full Red
  - `0,255,0` → Full Green
  - `0,0,255` → Full Blue
  - `0,0,0` → LED off
- The Arduino reads the serial input, parses the RGB values, and applies them to the corresponding pins.

---

## 💼 Portfolio

Check out more of my work and projects here:  
🔗 [My Portfolio](https://sites.google.com/d/1kRYFgoPpI5KiRHlfU4u9C--i8z4OA6I5/p/1_ZLDAirpPNf5aijgyz-LQdDFrC5D1Gd2/edit)

---

## 🔬 Simulation

Try the project in your browser using **Tinkercad**:

▶️ [Tinkercad Simulation - RGB with Serial Monitor](https://www.tinkercad.com/things/aP8z2WPV1OT-rgb-serial-mon-practionexample)

---

## 🙌 Credits

- Project by **[Madison Diggs]**
- Built using **Arduino Uno R3**
- Inspired by interactive lighting control systems

---

## 📄 License

This project is open-source and available under the Code in Schools.

---
