# Vedic Multiplier in Verilog

## Overview
This project implements a Vedic multiplier for 2x2, 4x4, and 8x8 bit multiplication using Verilog. Vedic multipliers are based on ancient Indian Vedic mathematics principles, which enable fast and efficient multiplication.

## Files
- `design_vedic_8x8.sv`: Contains the Verilog code for the half adder, multi-bit adders, and Vedic multipliers (2x2, 4x4, and 8x8).
- `testbench_vedic_8.sv`: Testbench for simulating and verifying the functionality of the 8x8 Vedic multiplier.

## Modules
- **Half Adder**: Computes the sum and carry of two single-bit inputs.
- **Adders**: Performs binary addition for 4-bit, 6-bit, 8-bit, and 12-bit numbers.
- **Vedic 2x2 Multiplier**: Multiplies two 2-bit inputs and produces a 4-bit output.
- **Vedic 4x4 Multiplier**: Uses four 2x2 multipliers and adders to perform 4x4 multiplication.
- **Vedic 8x8 Multiplier**: Uses four 4x4 multipliers and adders to perform 8x8 multiplication.

## Usage
1. Clone the repository:
   <a href="https://github.com/kk-abhishek/VerilogX_Vedic_Multiplier.git" target="_blank">Click here to clone the repository</a>

2. Simulation
You can test and simulate the Vedic multiplier design on <a href="https://www.edaplayground.com/x/BU6p" target="_blank">EDA Playground</a>.
