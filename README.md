# DC Buck-Converter (12V–75V → 10V, 400mA)

A KiCad-designed DC buck-boost converter using the LN5007MM PWM 
controller IC.

## Specifications
- Input Voltage  : 12V to 75V
- Output Voltage : 10V (regulated)
- Output Current : 400mA
- Controller IC  : LN5007MM
- Schottky Diode : SS110 (1A / 100V)
- Inductor       : L1 - 100µF
- PCB Tool       : KiCad EDA 9.0.7

## Block Description
| Block | Function |
|-------|----------|
| Input Power Stage | Input filtering, decoupling caps (C1, C5), R2 divider |
| PWM Controller Stage | LN5007MM, feedback resistor R5 |
| Output Filter Stage | L1, D1, C3/C4, R1/R4 feedback divider |

## Schematic Preview
![Schematic](Buck converter.pdf)

## Status
- [x] Schematic complete
- [ ] PCB Layout
- [ ] Gerber files
- [ ] BOM (Bill of Materials)

## Tools Used
- KiCad EDA

