# FPGA Vending Machine Controller

## Overview

This project implements a vending machine controller using Verilog HDL.

The controller is designed using a Finite State Machine (FSM) and simulates the behavior of a real vending machine by accepting coins, allowing product selection, and dispensing products with change when required.

This project was developed as part of my FPGA-Based System Design coursework.

---

## Features

- Verilog RTL implementation
- Finite State Machine (FSM)
- Supports multiple coin inputs
- Product selection logic
- Change dispensing
- Simulation using ModelSim
- Designed for FPGA implementation

---

## Technologies Used

- Verilog HDL
- Quartus II
- ModelSim
- FPGA

---

## Project Structure

```
├── vending_machine.v
├── vending_machine_tb.v
├── README.md
```

---

## Working

1. User inserts coins.
2. FSM updates the current balance.
3. User selects a product.
4. If sufficient balance exists:
   - Product is dispensed.
   - Remaining change is returned.
5. Otherwise, the machine waits for additional coins.

---

## FSM States

- Idle
- Coin Input
- Product Selection
- Dispense Product
- Return Change

---

## Learning Outcomes

- FSM Design
- Sequential Logic
- Verilog RTL Coding
- Testbench Development
- FPGA Design Flow

---

## Future Improvements

- LCD Display
- More Products
- Cancel Transaction
- Timeout Feature
