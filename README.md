# MIPS32 Pipeline Processor Design

This repository implements a pipelined MIPS32 processor in Verilog. The processor supports essential instructions and includes hazard handling and forwarding mechanisms.

## Features
- Five-stage pipeline: IF, ID, EX, MEM, WB
- Instructions: ADD, SUB, AND, OR, SLT, MUL, LW, SW, ADDI, SUBI, SLTI, Branches (BEQZ, BENQZ), HALT
- Memory of 1024 words
- Registers: 32 general-purpose registers
- Hazard detection and branching support

## Directory Structure
- **src/**: Contains the Verilog implementation of the processor.
- **testbench/**: Testbench and memory initialization files for simulations.
- **docs/**: Documentation of the architecture and pipeline flow.

## Getting Started
### Prerequisites
- Verilog simulator (ModelSim, Icarus Verilog, etc.)

### Running the Simulation
```bash
make simulate
