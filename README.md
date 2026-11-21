# ⚡ NIDAR – Hardware Development & Documentation

<p align="center">
  <b>Engineering • Electronics • Hardware Development</b>
  <br>
  Documentation and development of hardware tasks for NIDAR.
</p>

---

## 📌 About the Project

This repository documents the hardware development activities
undertaken as part of the **NIDAR Competition**.

The primary objective is to design and develop a microcontroller-
controlled adjustable **0–10V analog signal output system**.

The project covers the complete engineering workflow, starting
from understanding the requirements and researching circuit
architectures to electrical calculations, circuit design,
hardware implementation, and testing.

This repository serves as a technical record of the design
process, engineering decisions, calculations, and implementation.

---

## 🎯 Project Objectives

- Understand the requirements of a 0–10V analog signal output.
- Research suitable DAC and operational amplifier architectures.
- Develop a functional hardware block diagram.
- Perform necessary electrical calculations.
- Design and validate the electronic circuit.
- Develop the PCB using KiCad.
- Implement and test the hardware.
- Verify output voltage accuracy through measurements.

---

## 📚 Task Documentation

Each task is documented separately for easy access and reference.

| Task | Description | Documentation |
|---|---|---|
| 01 | 0–10V Signal Understanding | [View Task 01](Task1_0-10V_Signal.html) |
| 02 | 0–10V Circuit Research | [View Task 02](Task2_0-10V_Circuit_Research.html) |
| 03 | Hardware Block Diagram | [View Task 03](Task3_0-10V_Block_Diagram.html) |
| 04 | Electrical Calculations | [View Task 04](Task4_0-10V_Electrical_Calculations.html) |

---

## ⚙️ Technical Scope

The development process involves the following areas:

### 1. Signal Generation
Understanding the requirements and characteristics
of a variable 0–10V analog output.

### 2. Circuit Architecture
Researching suitable electronic components and
signal-generation architectures, including:

- Digital-to-Analog Conversion (DAC)
- Operational Amplifiers
- Signal Conditioning
- Voltage Scaling

### 3. Hardware Design
Developing the system architecture and circuit
schematics based on the selected design approach.

### 4. Electrical Calculations
Performing calculations related to:

- Voltage scaling
- Component selection
- Resistor networks
- Amplifier configurations
- Power requirements

### 5. PCB Development
Circuit development and PCB design using KiCad,
including layout and Design Rule Checks (DRC).

### 6. Hardware Testing
Testing the implemented circuit and verifying
the output voltage at different setpoints:

- 0V
- 5V
- 10V

---

## 🛠️ Tools & Technologies

| Tool / Technology | Application |
|---|---|
| KiCad | Circuit schematic and PCB design |
| HTML | Technical documentation |
| Electronics | Hardware development |
| DAC | Analog signal generation |
| Operational Amplifiers | Signal conditioning |
| Digital Multimeter | Voltage measurement and testing |

---

## 📂 Repository Structure

```text
NIDAR-HARDWARE-TASKS/
│
├── README.md
│
├── Task1_0-10V_Signal.html
│
├── Task2_0-10V_Circuit_Research.html
│
├── Task3_0-10V_Block_Diagram.html
│
└── Task4_0-10V_Electrical_Calculations.html