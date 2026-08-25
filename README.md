# KeeBord!
Keebord is my ~60% custom keyboard that i built to fit my gaming needs! I will add a KeePad soon after this!
It has 5 rows and 15 columns of keys! (although the last column is like 1 key lol)
# Key features!
-> 59 Keys (60 if including the joystick)
-> Joystick to use as a yoke in flight sims or just general analog input that isnt a mouse
-> Raspberry PI_Pico with USB support and 40 pins
-> Custom placement, custom design, Custom firmware, and custom KiCad layout!
I personally feel like this project taught me A LOT about Kicad, Coding and just the design part of the world in general, along with the standard process of making simple objects that most don't get to see.

Initially, I was going to make a 65% keyboard with no addiitonal parts, but since i was planning on playing some rc flight simulators in preparation for a different project, i thought it;d be a GREAT idea to add a baby joystick!
<img width="1131" height="684" alt="image" src="https://github.com/user-attachments/assets/28e26fee-0188-49cc-90da-ff1e912cd021" />


## Technical Overview

### Electronics & Hardware Setup
* **Microcontroller:** Raspberry Pi Pico (RP2040) running Python-based firmware.
* **Switch Matrix:** 5 rows and 14 columns utilizing a diode-isolated matrix (COL2ROW orientation with 1N4148 diodes) to prevent ghosting across all 59 primary mechanical keys.
* **Analog Controller:** 2-axis analog thumbstick wired directly to RP2040 ADC channels (`ADC0`/`GP26` for X-axis and `ADC1`/`GP27` for Y-axis) to emulate pitch and roll axis control for simulators.
* **PCB Design:** Custom 2-layer FR-4 circuit board designed in KiCad, routing power, row/col matrix connections, and analog signals down to a single compact footprint.

### Enclosure & Ergonomics
* **Case:** Custom 3D printable shell designed in Blender and exported as standard `.STEP` assembly geometry.
* **Plate Integration:** Integrated mounting points providing rigid mounting for hot-swap switch sockets and structural support across the 300mm x 100mm footprint.

---

## How to Use KeeBord

1. **Plugging In:** Connect the onboard Raspberry Pi Pico to your PC via a USB-C cable.
2. **Standard Typing:** Typing functions out-of-the-box as a standard 60% mechanical layout with complete key rollover.
3. **Joystick Control:** In flight simulators or space games, map `ADC0` and `ADC1` to primary yoke or throttle axes inside your simulator keybind settings.
4. **Firmware Customization:** To remap key assignments, simply edit `firmware/code.py` using any text editor—no compiling or specialized flashed toolchains required.

---

## Bill of Materials (BOM)

| Component | Quantity | Description | Unit Price | Total Price |
| :--- | :---: | :--- | :---: | :---: |
| Custom KeeBord PCB | 1 | 2-Layer Custom Printed Circuit Board (300mm x 100mm) | $18.40 | $18.40 |
| Raspberry Pi Pico | 1 | Microcontroller Board (RP2040) | $4.00 | $4.00 |
| MX Mechanical Switches | 59 | Linear/Tactile MX Style Key Switches | $0.20 | $11.80 |
| 1N4148 Switching Diodes | 59 | Signal Diodes for Matrix Isolation | $0.02 | $1.18 |
| Analog Joystick Module | 1 | 2-Axis Thumb Joystick (Potentiometer) | $1.50 | $1.50 |
| Keycap Set | 1 | Standard 60% MX Keycap Set | $12.00 | $12.00 |
| 3D Printed Case | 1 | Custom Blender Enclosure (PLA) | $5.00 | $5.00 |
| **Total Estimated Cost** | | | | **$53.88** |



---

# thanks :)
