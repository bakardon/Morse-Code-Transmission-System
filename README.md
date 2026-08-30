# Morse Code Transmission System on FPGA

**Verilog HDL implementation of a hardware Morse-code transmitter with FSM control, FIFO buffering, input debouncing, and seven-segment feedback.**

This Computer Engineering project implements a digital Morse-code transmission system on FPGA hardware. It combines sequential control logic, timing generation, buffered input, and user feedback into a single hardware design.

## Highlights

- Finite-state-machine based transmission control
- International Morse timing logic
- FIFO buffering for sequential message transmission
- Input debouncing for reliable physical controls
- Immediate and sequential transmission modes
- Seven-segment display feedback

## Architecture

```text
User Input
   ↓
Debouncing / Input Control
   ↓
FIFO Buffer ───────┐
   ↓               │
FSM Controller ←───┘
   ↓
Morse Timing Logic
   ↓
Transmission Output
   ↓
Seven-Segment Feedback
```

## Technology

**Verilog HDL · FPGA · FSMs · FIFO · Digital Logic · Hardware Timing**

## Project Context

Developed as a Computer Engineering digital-system project. The repository retains the original implementation and supporting project material.

## Why it matters

This project demonstrates hardware-oriented problem solving beyond software development: translating a behavioral specification into clocked digital logic, managing sequential state, handling noisy physical input, and coordinating multiple hardware components.
