## Parts:
- ESP32 Development Board or Raspberry Pi Pico W (more research)
- Analog Thumbstick Module (search up tmr or hall effect)
- Tactile Push Buttons
- Power Source (batteries)
## Skills Needed:
- Wiring
- Soldering
- Python
- 3D Design and Printing
## Software needed:
- KiCAD
- Blender or onshape (search up differences)



## Development Board Pro/cons
- ESP32 is faster
- Pico is cheaper
- ESP32 has USB-C
- Interesting link: https://documentation.espressif.com/esp32-s3_datasheet_en.pdf
- Also check this out: https://www.bluetooth.com/specifications/specs/hid-over-gatt-profile/


Research Notes: Printed Circuit Boards (PCBs)
1. What is a PCB?
- PCB stands for Printed Circuit Board.
- It is a board that physically holds and electrically connects electronic components.
- It replaces many loose wires with organized copper pathways.
2. Main PCB components
- Substrate: Insulating material that provides the board's structure.
- Copper traces: Conduct electricity between components.
- Solder mask: Protective coating, usually green.
- Silkscreen: Printed labels identifying components and connections.
3. PCB design
- A schematic is an electrical diagram showing how components connect.
- PCB layout determines where components physically sit on the board.
- Footprints represent the physical pad arrangements of components.
- Gerber files are used to send PCB designs to manufacturers.
4. Types of component mounting
- Through-hole: Component leads pass through holes in the board.
- SMD (Surface Mount Device): Components are mounted directly onto surface pads.
5. Software
- KiCad is free, open-source PCB design software.
- It allows users to create schematics and physical PCB layouts.
6. Relevance to my project
- A custom PCB could connect the ESP32, joystick, buttons and battery circuitry.
- It would make the final joystick mouse more compact and organized.
- Prototyping on a breadboard before designing a PCB is recommended.

In my own words, the PCB is essentially what is under the hood but then the casing is like the polished feel!