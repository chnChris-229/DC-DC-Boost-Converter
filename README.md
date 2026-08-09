# LM2577 DC-DC Boost Converter

A custom DC-DC boost converter designed in KiCad using the LM2577-ADJ switching regulator.

The circuit is designed to step a **9 V input** up to approximately **20 V output**. This project covers the full PCB design process, including schematic capture, component selection, PCB layout, routing, copper pours, design-rule checking, and Gerber/drill file generation.


## Features

- 9 V input
- Approximately 20 V output
- LM2577-ADJ switching regulator
- 180 µH inductor
- Schottky diode
- Input and output filtering capacitors
- Feedback resistor network
- Two-layer PCB
- Ground copper pour
- Through-hole component layout
- Gerber and Excellon drill files generated
- PCB Design Rule Check completed

## Schematic

![Boost Converter Schematic](Images/DC-DC boost converter 2)

## 3D PCB View

![PCB 3D View](Images/DC-DC boost converter)

## Repository Structure

```text
DC-DC-Boost-Converter/
│
├── README.md
│
├── KiCad/
│   ├── DC-DC boost converter.kicad_pro
│   ├── DC-DC boost converter.kicad_sch
│   ├── DC-DC boost converter.kicad_pcb
│   └── sym-lib-table
│
├── Gerbers/
│   ├── F_Cu.gbr
│   ├── B_Cu.gbr
│   ├── F_Mask.gbr
│   ├── B_Mask.gbr
│   ├── F_Silkscreen.gbr
│   ├── B_Silkscreen.gbr
│   ├── Edge_Cuts.gbr
│   ├── PTH.drl
│   ├── NPTH.drl
│   └── job.gbrjob
│
└── Images/
    ├── schematic.png
    ├── pcb-layout.png
    └── pcb-3d.png
