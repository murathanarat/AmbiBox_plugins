# Lightpack LED Animation Project 💡🔥⚡

This project is a Python-based LED animation system designed for **Lightpack / Prismatik** compatible LED setups.  
It controls **111 LEDs** placed around a monitor (top, bottom, left, and right) and provides multiple ambient lighting effects.

## 🎯 Project Purpose

- Create dynamic LED animations using Lightpack  
- Provide ambient lighting (ambilight / decorative effects)  
- Simulate realistic effects such as **fireplace**, **lightning**, and **snake** animations  

## 🧩 LED Layout

| Area   | LED Range | LED Count |
|-------|-----------|-----------|
| Top   | 1 – 30    | 30        |
| Bottom| 31 – 60   | 30        |
| Left  | 61 – 80   | 20        |
| Right | 81 – 111  | 31        |
| **Total** |  | **111** |

## 🚀 Technologies Used

- Python 3
- pyLightpack
- Lightpack / Prismatik
- TCP connection (`127.0.0.1:3636`)

## 📦 Requirements

- Python 3.x
- Prismatik or Lightpack software running

Install dependency:
```bash
pip install pylightpack
