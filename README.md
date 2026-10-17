# Custom-Buck-Converter-PCB
A custom buck converter PCB designed in KiCad, using the Texas Instruments TPS54202DDCR step-down voltage regulator IC sourced from LCSC Electronics.

This project documents the design of a custom DC-DC buck converter printed circuit board. The converter is designed to step down DC inout volatge to a lower DC output voltage.


Project Goals
- Design buck converter schematic and PCB
- Select appropriate components for the inetended volatge and current requiremnets
- Develop a PCB layout

Specifications
- Regulator IC: TPS54202DDCR
- Converter Type: Synchronous buck (step-down)
- Input Voltage: 4.5–28 V DC (IC operating range; board-level limits depend on the complete design)
- Output Voltage: Adjustable via the feedback resistor divider
- Maximum Output Current: 2 A (IC rating; actual capability depends on thermal performance and component selection)
- Switching Frequency: 500 kHz
- EDA Software: KiCad  
