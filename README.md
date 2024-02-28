# PCB-Design
Breadboard Power Supply PCB Design using KiCad
**Overview**
This repository contains the files for a breadboard power supply PCB design created using KiCad version 7. The project aims to provide a step-by-step guide on designing a PCB from scratch using KiCad, from schematic capture to manufacturing.

**Files Included**
Schematic: The schematic diagram (.sch) file outlines the circuit components and connections.
PCB Layout: The PCB layout (.kicad_pcb) file represents the physical layout of components on the PCB.
Gerber Files: Gerber files (.gbr) are included for manufacturing the PCB.
Bill of Materials (BOM): A BOM (.csv) listing all components used in the design.
3D Models: 3D models (.step) of components for visualization.

**Design Process**
**1. Schematic Design**
Launch KiCad and create a new project.
Draw the schematic diagram by adding components from the KiCad library.
Connect components using wires to represent electrical connections.
Label nets and add necessary annotations.
Check for errors and annotate the schematic.
Save the schematic.

**2. PCB Layout**
Open the PCB layout editor in KiCad.
Import the netlist generated from the schematic.
Place components on the PCB layout, considering factors like component orientation, size, and signal routing.
Route traces to connect components, ensuring proper clearance and avoiding signal interference.
Add necessary design elements like mounting holes, silkscreen labels, and copper pours.
Perform design rule checks (DRC) to ensure the design meets manufacturing requirements.
Generate Gerber files for manufacturing.

**3. Manufacturing**
Upload Gerber files to a PCB manufacturer's website.
Specify manufacturing options such as board material, thickness, and surface finish.
Review design files and confirm the order.
Wait for the manufacturer to produce and deliver the PCBs.
