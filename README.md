# CIS-310-assignment1-registers-sram
## Registers, Program Counter, Instruction Register, and SRAM Design

This project implements several core processor components using the Digital logic simulator.

## Implemented Components

- **Reg8** – 8-bit synchronous register with load and clear
- **GPR_Block** – 4-register general-purpose register file
- **PC_Block** – Program Counter with reset, increment, and load functionality
- **IR_Block** – Instruction Register
- **SRAM_Block** – 8-bit wide memory with 4-bit address space (16 locations)

Each component was designed and verified independently before being integrated.

---

## Integrated Demonstrations

### Demo 1 – Register to SRAM
Demonstrates writing data from the GPR block into SRAM at a selected address.  
Tests include correct register selection, write enable behavior, overwriting addresses, and multi-address verification.

### Demo 2 – SRAM to Instruction Register
Demonstrates reading data from SRAM and loading it into the Instruction Register.  
Verifies proper latching behavior and independence of the IR after loading.

---

## Repository Contents

- `Registers_SRAM.dig` – Top-level file
- `GPR_Block.dig`
- `PC_Block.dig`
- `IR_Block.dig`
- `SRAM_Block.dig`
- `/screenshots` – Test results for each block and demonstration

---

## Summary

This project demonstrates correct implementation of synchronous registers, memory, and controlled data transfer between processor components. All modules function independently and operate correctly when integrated.
