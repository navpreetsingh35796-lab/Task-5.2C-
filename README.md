# SIT210 Task 5.2C – Change the Light Intensity Using GUI

**Name:** Navpreet  
**Roll No:** 2510994811  
**Unit:** SIT210 – Embedded Systems Development  
**Task:** 5.2C – Change the Light Intensity Using GUI

---

## 1. Overview

This project extends the GUI developed for Task 5.1P. The purpose of this task is to control the intensity of a living room LED using a GUI slider and PWM on a Raspberry Pi.

The user can turn the living room LED ON or OFF and adjust its brightness from 0% to 100% using the intensity slider.

---

## 2. Hardware Required

- Raspberry Pi with Raspberry Pi OS
- LED
- 220Ω resistor
- Breadboard
- Jumper wires
- Keyboard, mouse and monitor

---

## 3. Software Used

- Python 3
- Tkinter
- RPi.GPIO

---

## 4. GPIO Configuration

| Component | GPIO Pin |
|---|---|
| Living Room LED | GPIO 18 |
| Resistor | 220Ω |
| Ground | GND |

GPIO 18 is used as the PWM output for controlling the brightness of the living room LED.

---

## 5. System Flow

```text
User
  ↓
Tkinter GUI
  ↓
Python Control Program
  ↓
PWM Generation
  ↓
Raspberry Pi GPIO 18
  ↓
220Ω Resistor
  ↓
Living Room LED
  ↓
GND
