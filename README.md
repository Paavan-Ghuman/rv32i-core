RISC-V RV32I Processor Core

Implementation of a 32-bit RISC-V processor (RV32I) designed in SystemVerilog and simulated using ModelSim and GTKWave. The processor follows a 5-stage pipeline architecture and demonstrates core concepts of modern CPU design including hazard handling and pipeline control. 

Project Summary

This project implements the base RV32I instruction set architecture using a classic pipelined CPU design. The processor supports instruction execution through the five standard stages:

Instruction Fetch (IF)

Instruction Decode (ID)

Execute (EX)

Memory Access (MEM)

Write Back (WB)

Pipeline control mechanisms are included to handle data hazards, stalls, and forwarding paths during instruction execution. 

Main Components

Fetch Unit – Retrieves instructions from memory and updates the program counter

Decode Unit – Interprets instructions and reads operands from registers

ALU / Execute Unit – Performs arithmetic, logical, and branch operations

Memory Unit – Handles load and store instructions

Writeback Unit – Writes computation results back to the register file

Tools Used

SystemVerilog – Hardware design and module implementation

ModelSim / QuestaSim – Simulation and verification

GTKWave – Signal waveform visualization

Icarus Verilog – Alternative open-source simulator