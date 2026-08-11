# FIFO-16x8-Verilog
16x8 FIFO memory designed and verified using Verilog RTL and ModelSim.

# 16x8 FIFO Memory using Verilog RTL

## Overview

This project implements a 16x8 FIFO memory using Verilog RTL.

FIFO stands for First-In First-Out. The data written first into the FIFO is read first.

## Specifications

- FIFO Depth: 16 locations
- Data Width: 8 bits
- Address Width: 4 bits
- Counter Width: 5 bits
- Synchronous read and write
- Active-high synchronous reset
- Full and empty status signals

## Features

- Write operation
- Read operation
- FIFO data ordering
- Full condition detection
- Empty condition detection
- Reset functionality

## Design

The FIFO consists of:

- 16x8 memory array
- Write pointer
- Read pointer
- Data counter
- Full flag
- Empty flag

## Files

| File | Description |
|---|---|
| `fifo_16x8.v` | FIFO RTL design |
| `fifo_16x8_tb.v` | Verilog testbench |

## Tools Used

- Verilog HDL
- ModelSim Intel FPGA Starter Edition 2020.1

## Verification

The testbench verifies:

1. Reset operation
2. Write operation
3. Read operation
4. FIFO data sequence
5. Full condition
6. Empty condition

## FIFO Operation

Data is written into the FIFO using `wr_en` and read using `rd_en`.

The FIFO follows First-In First-Out ordering.

## Author

Akhilesh Bhuskute
