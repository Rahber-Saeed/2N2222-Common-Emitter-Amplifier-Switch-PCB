# 2N2222-Common-Emitter-Amplifier-Switch-PCB
A straightforward DIY PCB implementing a classic 2N2222 NPN transistor circuit. Designed for electronics labs, this board provides a clean layout for testing common-emitter amplifier or switching applications. Perfect for learning or as a general-purpose signal buffer.
# ⚡ ECD LAB Project: 2N2222 NPN Transistor Circuit

This repository contains the complete hardware design files for a simple, robust PCB built around the **2N2222 NPN transistor**. 

It is designed to function as a classic **Common Emitter Amplifier** or a transistor-based **Signal Switch**. With through-hole components for easy assembly, this board is ideal for electronics education, lab experiments, and prototyping audio or signal handling applications.

> ⚠️ **Note:** This board requires basic soldering skills and external jumper wires. The board is designed to accept standard DC power (`VCCINPUT`) and an AC/DC signal (`VINAC`).

---

## 📌 Key Features

*   **Core Component:** 2N2222 NPN Transistor.
*   **Inputs:** Power Input (`VCCINPUT`) and AC/DC Signal Input (`VINAC`).
*   **Output:** Buffered Signal Output (`OUTPUT`).
*   **Passives:**
    *   4x 1kΩ resistors (RC, RE, R1, R2).
    *   3x 1uF capacitors (C1, C2, C3).
*   **Design:** Compact, single-layer PCB using standard, easy-to-find through-hole components.

---

## 🖼️ Gallery

| PCB Layout | Schematic |
<img width="1170" height="827" alt="Schematic_ECD_LAB_Projrct_2026-05-03" src="https://github.com/user-attachments/assets/8d875048-edea-4fc6-83cc-e76742824a95" />

| :---: | :---: |
<img width="581" height="566" alt="ECD_LAB_Projrct_3D_Top_View" src="https://github.com/user-attachments/assets/38cd7ffa-dbc0-4d8e-90e3-cdf8899bbe93" />

| [![PCB Layout](images/PCB_Layout.png)](images/PCB_Layout.png) | [![Schematic](images/Schematic.png)](images/Schematic.png) |
<img width="603" height="600" alt="ECD_LAB_Projrct_3D_Bottom_View" src="https://github.com/user-attachments/assets/c32fb338-6807-4d09-acdd-0644bf262c34" />


---
<img width="597" height="582" alt="ECD_LAB_Projrct_2D_View" src="https://github.com/user-attachments/assets/b0413546-9235-4346-8eaa-9aad778f9e22" />

## 📌 Pinout & Connections

| Connector | Pin | Function |
| :--- | :--- | :--- |
| **VCCINPUT** | Pin 1 | Power Input (VCC) |
| | Pin 2 | Ground (GND) |
| **VINAC** | Pin 1 | Signal Input (AC/DC) |
| | Pin 2 | Ground (GND) |
| **OUTPUT** | Pin 1 | Signal Output |
| | Pin 2 | Ground (GND) |

*(Note: The labeling on the PCB schematic may differ slightly depending on the revision. Always verify with the `Schematic_ECD_LAB_Projrct...pdf` file before applying power).*

---

## 📦 Bill of Materials (BOM)

The complete list of components required to build this project is provided in the [`BOM_ECD_LAB_Projrct_2026-05-03.csv`](BOM_ECD_LAB_Projrct_2026-05-03.csv) file.

| Component | Quantity | Description |
| :--- | :--- | :--- |
| Q1 | 1 | 2N2222 NPN Transistor |
| R1, R2, RC, RE | 4 | 1kΩ Resistor |
| C1, C2, C3 | 3 | 1uF Capacitor |
| VCCINPUT, VINAC, OUTPUT | 3 | 1x2 Female Header (2.54mm) |

---

## ⚙️ Assembly & Usage

1.  **Order the PCB:** Upload the `PCB_ECD_LAB_Projrct...pdf` to a manufacturer like JLCPCB, PCBWay, or Aisler.
2.  **Source Components:** Use the BOM CSV file to purchase the required parts.
3.  **Assembly:** Solder all through-hole components onto the PCB. Pay attention to the orientation of the 2N2222 transistor (flat side facing the correct way).
4.  **Testing:** 
    *   Connect a power supply to `VCCINPUT` (e.g., 5V-12V DC).
    *   Connect an audio source, microphone, or a low-frequency square wave generator to `VINAC`.
    *   Connect an oscilloscope or speaker to `OUTPUT` to observe the amplified/switched signal.

---

## 🗂️ Repository Structure
