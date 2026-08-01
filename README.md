# 5-Bit Manchester Carry Lookahead Adder

A transistor-level implementation of a **5-bit Manchester Carry Lookahead Adder (MCLA)** designed for high-speed arithmetic operations. The project includes schematic design, Verilog implementation, SPICE simulations, physical layout, and FPGA verification.

## Features

- 5-bit Manchester Carry Lookahead Adder
- TSPC (True Single Phase Clock) D Flip-Flops
- PTL-based XOR implementation
- Transistor-level CMOS design
- Timing, delay, and area analysis
- Functional verification through Verilog, NGSpice, Magic VLSI, and FPGA

## Tools Used

- Verilog HDL
- NGSpice
- Magic VLSI
- AMD FPGA Development Board

## Results

- Worst-case carry chain delay: **769 ps**
- Maximum operating frequency: **834 MHz**
- Layout area: **19,420 μm²**

## Repository Structure

```
.
├── MAGIC/
│   ├── Layout files
│   └── DRC/LVS related files
│
├── NGSPICE/
│   ├── Schematics
│   ├── SPICE netlists
│   └── Simulation files
│
├── VERILOG/
│   ├── RTL modules
│   ├── Testbenches
│   └── Simulation outputs
│
├── 5Bit-MCA Project report.pdf
└── README.md
```

## Verification

The design was validated through:

- Transistor-level simulations in **NGSpice**
- Functional verification in **Verilog**
- Physical layout using **Magic VLSI**

## Author

**Vedant Zope**
