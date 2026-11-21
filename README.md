# NIDAR 0–10V Analog Signal Generator

**An adjustable 0–10V analog output stage, taken from first-principles research through simulation to PCB layout.**

Developed by the hardware team for the **NIDAR** competition.

---

## Overview

Many industrial controllers, drives and sensors expect a standard 0–10V analog control signal. This project designs a compact, adjustable signal source that produces that range from a digital input, and documents every engineering decision on the way: why the topology was chosen, how the numbers were derived, how the design behaves in simulation, and how it was laid out as a board.

The repository is both a design record and a reproducible starting point. Anyone should be able to open the files, follow the reasoning, and rebuild or extend the design.

## Design Workflow

```
Research  →  Block Diagram  →  Calculations  →  Simulation  →  PCB Layout  →  Fabrication  →  Validation
 (done)         (done)           (done)          (done)          (done)        (pending)       (pending)
```

## Repository Contents

| Path | Stage | Description |
| --- | --- | --- |
| [`Task1_0-10V_Signal.html`](Task1_0-10V_Signal.html) | Introduction | What a 0–10V signal is and why it is used |
| [`Task2_0-10V_Circuit_Research.html`](Task2_0-10V_Circuit_Research.html) | Research | Survey of candidate circuit approaches and trade-offs |
| [`Task3_0-10V_Block_Diagram.html`](Task3_0-10V_Block_Diagram.html) | Architecture | System-level block diagram of the signal chain |
| [`Task4_0-10V_Electrical_Calculations.html`](Task4_0-10V_Electrical_Calculations.html) | Analysis | Component selection and electrical calculations |
| [`DAC_0-10V.asc`](DAC_0-10V.asc) | Simulation | First LTspice iteration of the circuit |
| [`DAC_0-10V final simulation.asc`](DAC_0-10V%20final%20simulation.asc) | Simulation | Final, refined LTspice model |
| [`pcb.kicad_pcb`](pcb.kicad_pcb) | Hardware | KiCad board layout for the final circuit |

## Getting Started

**Read the documentation**
Download the repository (or clone it) and open the `Task*.html` files in any web browser. They are best read in order, Task 1 through Task 4.

```bash
git clone https://github.com/alennn2111-spec/NIDAR-HARDWARE-TASKS.git
cd NIDAR-HARDWARE-TASKS
```

**Run the simulation**
1. Install [LTspice](https://www.analog.com/en/resources/design-tools-and-calculators/ltspice-simulator.html).
2. Open `DAC_0-10V final simulation.asc`.
3. Run the simulation and probe the output node to inspect the 0–10V behaviour.

`DAC_0-10V.asc` is kept for reference so the evolution of the design is visible.

**Inspect the PCB**
1. Install [KiCad](https://www.kicad.org/).
2. Open `pcb.kicad_pcb` in the PCB Editor to review the layout, placement and routing.

## Tools

| Tool | Used for |
| --- | --- |
| LTspice | Circuit simulation and analysis |
| KiCad | PCB layout |
| HTML / CSS | Technical documentation |

## Project Status

| Milestone | Status |
| --- | --- |
| Initial and circuit research | Complete |
| System block diagram | Complete |
| Electrical calculations | Complete |
| LTspice simulation | Complete |
| PCB layout | Complete |
| PCB fabrication | Pending |
| Hardware assembly | Pending |
| Physical testing and validation | Pending |

## Roadmap

- Fabricate the PCB and assemble the first prototype
- Measure output accuracy, linearity and noise on the bench
- Compare measured results against the simulation
- Feed findings back into a revised layout if needed

## Contributing

Suggestions, corrections and design reviews are welcome. Please open an issue describing the change, or submit a pull request with a short explanation of what it improves.

## Author

**alennn2111-spec**, NIDAR hardware team.
