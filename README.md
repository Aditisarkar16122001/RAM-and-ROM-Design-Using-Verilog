# RAM-and-ROM-Design-Using-Verilog

# Verilog Memory Design – ROM & Single Port RAM

##  Project Overview
This repository contains Verilog HDL implementations of:

- 8-bit × 64 Single Port RAM
- 4-bit × 16 ROM
- Complete Testbenches
- Simulation waveform generation using Icarus Verilog

This project demonstrates understanding of:
- Memory architecture
- Synchronous design
- Write enable logic
- Registered addressing
- Testbench development
- Waveform verification

---

##  Modules Included

###  1. Single Port RAM (8 × 64)

- 8-bit data width
- 64 memory locations
- Synchronous write
- Registered read address
- Write enable controlled

#### Features:
- Write operation on `we = 1`
- Read operation on `we = 0`
- Uses address register for stable read output

 ----
###  2. ROM (4 × 16)

- 4-bit data width
- 16 memory locations
- Synchronous read
- Enable-controlled output

#### Features:
- Memory initialized using `initial` block
- Output updated on positive clock edge
- High impedance / unknown output when disabled


---

##  Simulation Tool

- Icarus Verilog
- EPWave for waveform viewing

---
