# RISC-V Processor Implementation in Verilog

This repository contains the implementation of a **32-bit RISC-V processor** written in **Verilog HDL**.  
The project demonstrates the design of both **Single-Cycle** and **5-Stage Pipelined RISC-V architectures**.

The processor executes a subset of **RISC-V RV32I instructions** and illustrates the internal datapath and control flow between major hardware components.

---

## 🚀 Features

- 32-bit RISC-V Processor
- Verilog HDL Implementation
- Single Cycle Architecture
- Modular Design
- Instruction Execution Flow
- Simulation Ready Design

---

##  Architecture

### Single Cycle Processor
Each instruction completes execution in **one clock cycle**.  
All datapath operations such as instruction fetch, decode, execute, memory access, and write back occur within a single cycle.

---

## ⚙️ Modules Implemented

- Program Counter (PC)
- PC Adder
- Instruction Memory
- Register File
- Control Unit
- ALU Control
- Arithmetic Logic Unit (ALU)
- Immediate Generator
- Data Memory

---

## 🔄 Datapath Flow

Instruction execution follows this flow:

Instruction Memory → Control Unit → Register File → ALU → Data Memory → Register File

---
