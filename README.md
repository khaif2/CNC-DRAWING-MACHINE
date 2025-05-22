# CNC-DRAWING-MACHINE
CNC Machine for Precision Automation Using G-Code
This repository contains the design, code, and configuration files for a custom-built CNC machine controlled via G-code commands. The machine is designed for tasks such as 2D plotting, engraving, or precision movement, controlled through open-source software and Arduino-based firmware.
🔧 Features
✅ 2-axis/3-axis CNC motion control using stepper motors

✅ Real-time G-code execution using Pronterface

✅ Arduino UNO (or Nano) running GRBL firmware

✅ Custom frame with lead screws and precision guides

✅ Compatible with laser/pen/pencil toolheads

✅ Manual and automated control over serial

🛠️ Tools & Technologies
Arduino IDE – for firmware uploading (GRBL or custom)

Pronterface – for sending G-code commands and real-time control

GRBL – open-source firmware for motion control via G-code

Stepper Drivers – A4988/DRV8825

3D Printed / Laser-cut frame components

Custom G-code scripts for drawing/logos/circuits

⚙️ How It Works
Firmware Setup:

Upload GRBL firmware to Arduino using Arduino IDE.

Connect stepper drivers and motors to the correct pins (as defined by GRBL).

Software Control:

Launch Pronterface (or Universal G-code Sender).

Connect to the COM port where Arduino is connected.

Send G-code commands like G1 X50 Y50 F1000 to move toolhead.

Toolhead Control:

Use G-code M3/M5 or servo commands to lift/lower pen or trigger laser.

Sample G-codes:

Circle: G2 I10

Line: G1 X100 Y100 F500

Pen up/down: M3 / M5 or G1 Z10

🧾 Applications
PCB plotting or engraving

Pen drawing robot (art bot)

Mini laser engraving

Educational robotics project
