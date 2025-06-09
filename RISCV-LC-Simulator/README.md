# RISCV-LC Simulator
A RISC-V LC Simulator is a lightweight software tool designed to emulate the behavior of a simplified RISC-V "Little Computer" (LC) processor for educational purposes.
It allows users to write, assemble, and debug RISC-V assembly programs in a controlled environment, often with reduced complexity compared to full-scale RISC-V implementations.

### The Key Features of a RISC-V LC Assembler:

- Simplified Instruction Set
- Integrated Assembler & Debugger
- Visualization Tools
- Educational Focus

## Get the RV321 Assembler

- git clone https://github.com/Ethannggggg/RISC-V-simulator.git

- cd RISC-V-simulator

- git checkout RISCV-LC-Assembler

## Run the assembler

### Assemble a RISC-V file and generate a binary
``` bash 
  ./riscv-lc uop [input.bin]
```
### Example:
```bash 
 ./riscv-lc uop benchmarks/isa.bin
```
- This is for checking the output machine code: isa.bin if you have implemented the assembler


