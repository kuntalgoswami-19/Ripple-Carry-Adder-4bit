# Ripple-Carry-Adder-4bit
This project demonstrates the design and simulation of a Ripple Carry Adder (RCA) using Verilog. A Ripple Carry Adder is one of the simplest forms of binary adders, where the carry output from each full adder is passed (or "rippled") to the next. It serves as a foundational concept in digital electronics and computer architecture.
The RCA is implemented using a modular approach:

A 1-bit Full Adder module

A 4-bit Ripple Carry Adder composed of chained Full Adders

This project is ideal for beginners learning digital logic design or working with FPGA/ASIC development using Verilog.

📁 Features
Fully modular and hierarchical Verilog design

Supports N-bit RCA design (default: 4-bit)

Testbench included for simulation and verification

Waveform analysis using GTKWave (optional)

🔍 Files Include

RCA.v: Verilog code for N-bit ripple carry adder

RCA_tb.v: Testbench to simulate RCA

README.md: Project documentation

🛠️ Tools Used
Verilog HDL

Simulation: ModelSim


📈 Simulation Output
Displays sum and carry outputs for various input combinations

Verifies correctness through waveform and console output
