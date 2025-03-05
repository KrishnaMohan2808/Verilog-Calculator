# Verilog-Calculator

This project implements an 8-bit calculator in Verilog that supports:
- Addition
- Subtraction
- Multiplication
- Division
- Modulo
- Bitwise AND, OR, XOR

## How to Run
1. Compile with Icarus Verilog.
 iverilog -o calculator_tb.out Calculator_tb.v Calculator.v

2. Run the simulation.
 vvp calculator_tb.out

3.View Waveform in GTKWave.
 gtkwave calculator_wave.vcd


