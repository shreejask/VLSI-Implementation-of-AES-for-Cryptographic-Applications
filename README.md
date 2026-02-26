# VLSI-Implementation-of-AES-for-Cryptographic-Applications

## Project Overview
This project implements the Advanced Encryption Standard (AES) algorithm using Verilog HDL.  
The design is developed for FPGA implementation and includes the RTL design file, XDC constraint file, and a testbench for simulation.

## Tools Used
- AMD Vivado 2025.1
- Verilog HDL
- FPGA Board

## Project Structure

The repository contains the following files:

- aes_top.v  
  Main RTL design file implementing the AES encryption module.

- aes.xdc  
  FPGA constraint file defining pin configuration and timing constraints.

- aes_tb.v  
  Testbench file used for functional simulation and verification of the AES design.

## Features
- 128-bit AES encryption implementation
- Modular hardware architecture
- Synthesizable RTL design
- Simulation support using testbench

## How to Run
1. Open Vivado.
2. Create a new project.
3. Add the design file (aes_top.v).
4. Add the constraint file (aes.xdc).
5. Add the testbench file (aes_tb.v).
6. Run simulation and synthesis.

## Author
Shreeja SK

## Description
This project demonstrates the hardware implementation of a cryptographic encryption algorithm using VLSI design methodology and FPGA-based development flow.
