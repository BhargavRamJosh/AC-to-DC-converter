# AC to DC Converter (12V AC to DC)

## 🔌 Project Overview
This project demonstrates the design of a **12V AC to DC Converter** using a **bridge rectifier, filter capacitor, and indicator LED**. The goal is to provide a **stable DC voltage output** suitable for powering low-power electronic circuits such as **Arduino boards, sensors, or basic embedded modules**.

---

## 📷 Project Images

| PCB Routing (Top View) | Schematic (KiCad) | 3D View |
|------------------------|-------------------|---------|
| ![PCB Routing](MEDIA/Screenshot%202025-10-03%20224038.png) | ![Schematic](MEDIA/Screenshot%202025-10-03%20224129.png) | ![3D View](MEDIA/Screenshot%202025-10-03%20224204.png) |

---

## ⚙ Circuit Working

| Stage | Component | Purpose |
|--------|-----------|---------|
| AC Input | Screw Terminal (J102) | Connect 12V AC from transformer |
| Rectification | 4× 1N4007 Diodes | Converts AC to pulsating DC |
| Filtering | 1000µF Capacitor (C101) | Smooths the DC output |
| Indicator | LED + 2.2k Resistor (R101) | Shows power status |
| Output | Screw Terminal (J101) | Provides DC Output |

---

## ✅ Features

- Converts **12V AC to smooth DC**
- Compact **single-layer PCB layout**
- **Visual power indicator (LED)**
- **DIY-friendly through-hole components**

---

## 🧾 Components List

| Component | Value / Type | Quantity |
|-----------|---------------|----------|
| Diodes | 1N4007 | 4 |
| Capacitor | 1000µF / 25V | 1 |
| Resistor | 2.2kΩ | 1 |
| LED | Red / 5mm | 1 |
| Terminal Block | 2-Pin | 2 |

---

## 🛠 Applications

- Power supply for **Arduino / ESP32**
- **Sensor modules**
- **Small lab experiments**
- **Testing DC circuits from AC source**

---

## 🧑‍💻 Author

**Bhargav Ram**  
Electronics & Communication Engineering  
Passionate about **Embedded Systems & PCB Design**

---

If you like this project, ⭐ the repo or suggest improvements!
