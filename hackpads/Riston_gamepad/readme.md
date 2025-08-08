# The "Macro-13" Custom Macropad

## Overview

The **Macro-13** is a custom-built, 13-key macropad designed to enhance gaming and productivity workflows. This project integrates a **0.96" OLED screen** and vibrant **SK6812 Neopixel RGB lighting** into a compact, custom-designed case. The macropad is powered by a **XIAO RP2040 microcontroller** and utilizes **KMK firmware**, making it fully programmable and easy to customize.

---

## Features

- **13 Programmable Keys:** A compact layout perfect for consolidating essential keys, whether for gaming, macros, or a dedicated numpad.
- **Dual-Function 13th Key:** A unique feature that allows a single press to cycle through various **Neopixel RGB color combinations**, while a double press switches between different keyboard modes (e.g., gaming, numpad, custom layouts).
- **Integrated OLED Display:** The 0.96" OLED screen provides real-time feedback, showing the active keymap, current layer, or custom graphics.
- **Dynamic Neopixel Lighting:** 9 SK6812 MINI-E LEDs are used for per-key and underglow lighting, creating a stylish and immersive gaming aesthetic.
- **Custom 3D-Printed Case:** A robust, two-part case (`case_top.stl` and `case_bottom.stl`) designed in Onshape to provide a secure and professional enclosure for the electronics.

---

## Project Motivation

I created the Macro-13 to have a dedicated gaming pad that prevents wear and tear on my laptop's keyboard. This project was also a valuable hands-on experience in electronics, PCB design, and 3D modeling, allowing me to build a unique and functional piece of hardware to share with others.

---

## Build Guide & Design

### CAD Design

The case was designed and iteratively refined in **Onshape**. The final design provides a secure and professional-looking enclosure using heatset inserts and M3 screws. The case geometry was also optimized to diffuse the RGB lighting, enhancing the overall visual appeal.

- **Onshape Public Document:**  <img width="1913" height="874" alt="image" src="https://github.com/user-attachments/assets/9254b6fd-e825-4567-8860-53f1aa45c890" />
- **STLs for 3D Printing:**
  - `case_top.stl`
  - `case_bottom.stl`

### PCB Design

The custom PCB was designed using **EasyEDA**. The layout was carefully verified to ensure reliability. The KiCad files and Gerbers are available in this repository.

- **Schematic:**<img width="1919" height="879" alt="image" src="https://github.com/user-attachments/assets/19e88a92-1738-4921-a559-d4c970dc2713" />


- **PCB Layout:**  <img width="1913" height="874" alt="image" src="https://github.com/user-attachments/assets/9254b6fd-e825-4567-8860-53f1aa45c890" />
- **Gerber Files:** [Link to Gerber files folder]

### Firmware

The firmware is based on **KMK**, a powerful and user-friendly firmware built on CircuitPython. The code includes support for the OLED screen and the dual-function 13th key.

- **Firmware Code:** [Link to your firmware folder]

---

## Bill of Materials (BOM)

| Item | Quantity | Notes |
| :--- | :--- | :--- |
| **Microcontroller** | 1 | XIAO RP2040 MCU |
| **Switches** | 13 | Cherry MX Keys |
| **Diodes** | 16 | 1N4148 Diodes |
| **LEDs** | 9 | SK6812 MINI-E LEDs |
| **Display** | 1 | 0.96" OLED Display |
| **Resistor** | 1 | 330 Ohm Resistor |
| **Capacitor** | 1 | 100uF 50V Capacitor, SMD |
| **PCB** | 1 | Custom-designed PCB |
| **Keycaps** | 13 | Your choice of keycaps |
| **Screws** | 8 | M3 Screws, 16mm |
| **Nuts** | 8 | M3 Hex Nuts |
| **Inserts** | 8 | Heatset Inserts |
| **Case** | 1 | `case_bot.stl` and `case_top.stl` |

---

## Future Plans

- Develop more advanced firmware with additional keymap layers.
- Explore adding a rotary encoder or a small joystick.
- Further refine the case design for a more polished aesthetic.
