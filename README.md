# 🧠 RV32I RISC-V Processor Core

A **32-bit RISC-V (RV32I) pipelined processor** implemented in **SystemVerilog** and verified using **ModelSim** and **GTKWave**.  
This project demonstrates the design and simulation of a classic **5-stage CPU pipeline** with hazard handling and forwarding mechanisms.

---

## 📌 Project Overview

This processor follows the **RISC-V RV32I instruction set architecture** and executes instructions through a five-stage pipeline:

1. **Instruction Fetch (IF)**
2. **Instruction Decode (ID)**
3. **Execute (EX)**
4. **Memory Access (MEM)**
5. **Write Back (WB)**

The implementation focuses on core **computer architecture concepts**, including pipeline control, instruction decoding, register operations, and instruction execution flow.

---

## ⚙️ Key Features

- ✅ 5-Stage CPU Pipeline  
- ✅ RV32I Base Instruction Set  
- ✅ Data Hazard Detection  
- ✅ Forwarding Logic for Pipeline Efficiency  
- ✅ Stall and Flush Control  
- ✅ Memory Read / Write Support  
- ✅ Modular SystemVerilog Architecture  

---

## 🧩 Architecture Components

| Component | Description |
|-----------|-------------|
| **Fetch Unit** | Retrieves instructions and updates the program counter |
| **Decode Unit** | Decodes instructions and reads register operands |
| **Execute Unit (ALU)** | Performs arithmetic, logic, and branch operations |
| **Memory Unit** | Handles load/store instructions |
| **Writeback Unit** | Writes results back to the register file |

---

## 🏗 Pipeline Architecture

```
Instruction Fetch → Instruction Decode → Execute → Memory → Write Back
        (IF)              (ID)             (EX)      (MEM)      (WB)
```

Pipeline registers separate each stage to enable **parallel instruction execution**.

---

## 🛠 Tools & Technologies

| Tool | Purpose |
|-----|--------|
| **SystemVerilog** | Hardware description and module implementation |
| **ModelSim / QuestaSim** | Simulation and debugging |
| **GTKWave** | Waveform visualization |
| **Icarus Verilog** | Alternative open-source simulator |

---

## 🎓 Academic Context

Developed as part of a **Computer Architecture course project**, exploring CPU pipeline design, instruction execution, and hardware verification techniques.

---