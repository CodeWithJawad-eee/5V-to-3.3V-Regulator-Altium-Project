# 5V-to-3.3V-Regulator-Altium-Project
A compact Altium Designer project that converts a 5V input to a regulated 3.3V output using the MIC5317 LDO voltage regulator. Includes schematic, PCB layout, and 3D model visualization.

🔋 5V to 3.3V Voltage Regulator – Altium Designer Project
📑 Project Overview
This project demonstrates the design and layout of a 5V to 3.3V Low Dropout (LDO) Voltage Regulator using Altium Designer. It is intended for applications that require a stable 3.3V power supply from a 5V input source, commonly found in embedded systems and IoT devices.

The design includes a compact and efficient layout with support for standard surface-mount components and connectors for easy integration into existing circuits.

⚙️ Features
Input Voltage: +5V DC

Output Voltage: +3.3V DC (regulated)

Voltage Regulator IC: MIC5317-3.3YD5-TR (Low Dropout LDO Regulator)

Input/Output Capacitors: 1µF ceramic capacitors for stability and noise filtering

Connectors: SM02B-GHS-TB(LF)(SN) for input and output connections

3D PCB View: Modeled and visualized in 3D using Altium’s 3D layout tools

👤 Who is this for?
Electronics and embedded systems enthusiasts

Engineering students learning PCB design

Hobbyists working on microcontroller projects

Anyone looking to power 3.3V components from a 5V source

Engineers or developers who want a reliable LDO-based power supply module

🧰 Requirements
Altium Designer (any recent version that supports 3D viewing)

Basic knowledge of electronics and circuit design

Understanding of how voltage regulators work

Soldering equipment (if physically assembling the board)

🔧 Components Used

Designator	Component	Description
J1	SM02B-GHS-TB(LF)(SN)	Input connector (5V)
J2	SM02B-GHS-TB(LF)(SN)	Output connector (3.3V)
C1	1µF Ceramic Capacitor	Input capacitor
C2	1µF Ceramic Capacitor	Output capacitor
U1	MIC5317-3.3YD5-TR	3.3V LDO voltage regulator
🖥️ Files Included
Schematic.SchDoc – Full circuit schematic

PCB.PcbDoc – PCB layout design

3D View.png – 3D visual of the PCB

Schematic.png – Annotated schematic diagram

Project Files – Altium project files (if uploaded)

📦 Applications
Power supply for 3.3V microcontrollers (ESP32, STM32, etc.)

Logic level converters

General embedded systems

Low-noise analog circuits

🛠️ Tools Used
Software: Altium Designer

Design Environment: 2D and 3D PCB Layout Editor

Libraries: Manufacturer Part Search + Custom footprints

📸 Previews
🔹 Schematic
![Schematic](https://github.com/user-attachments/assets/34eb2e49-d2e6-4210-ac72-0047f2f56fd7)


🔹 PCB 3D View
![PCB](https://github.com/user-attachments/assets/a4ac6c86-252c-4e64-a9b9-da6785a0a5eb)


📌 Notes
Ensure input voltage remains within safe operating limits for the regulator.

Decoupling capacitors (C1 and C2) should be placed as close to the IC as possible for stability.

This board is suitable for both prototyping and integration into finished products.

💬 Questions?
If you have any questions, feel free to contact me on LinkedIn.
