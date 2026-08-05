# 4x1 Multiplexer using Verilog

## Objective
To design and simulate a 4x1 Multiplexer using Verilog HDL.

## Description
A 4x1 Multiplexer selects one of four input signals and forwards it to a single output based on two select lines.

## Truth Table

| S1 | S0 | Output (Y) |
|----|----|------------|
| 0  | 0  | I0         |
| 0  | 1  | I1         |
| 1  | 0  | I2         |
| 1  | 1  | I3         |

## Files
1. mux4x1.v        - Verilog design code
2. mux4x1_tb.v     - Testbench
3. README.md       - Project documentation

## Software Required
- Xilinx Vivado
- ModelSim
- Icarus Verilog
- GTKWave (optional)

## How to Run
1. Compile mux4x1.v and mux4x1_tb.v.
2. Run the simulation.
3. Observe the waveform and output.

## Expected Result
The output Y should always match the selected input according to the select lines.