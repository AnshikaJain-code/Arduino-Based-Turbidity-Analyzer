# 🌊 Turbidity Sensor using Arduino Uno

## 📌 Overview
This project measures water quality using a turbidity sensor and displays the result on a 16x2 LCD screen.

Turbidity indicates how clear or cloudy water is. This system classifies water into:
- Clear Water
- Slightly Cloudy Water
- Highly Cloudy / Dirty Water

---

## 🧰 Components Used
- Arduino Uno
- Turbidity Sensor Module
- 16x2 LCD Display
- Breadboard
- Jumper Wires

---

## ⚙️ Working Principle
The turbidity sensor outputs an analog voltage based on water clarity.

- High voltage → Clear water
- Low voltage → Cloudy water

The Arduino:
1. Reads analog value from sensor
2. Processes the value
3. Displays both numeric value and water condition on LCD

---

## 🔌 Circuit Connections

| Component        | Arduino Pin |
|----------------|------------|
| Sensor VCC      | 5V         |
| Sensor GND      | GND        |
| Sensor OUT      | A0         |
| LCD RS          | D7         |
| LCD EN          | D6         |
| LCD D4          | D5         |
| LCD D5          | D4         |
| LCD D6          | D3         |
| LCD D7          | D2         |

---

