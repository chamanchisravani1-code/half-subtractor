# Half Subtractor using Verilog

## Overview

A Half Subtractor is a combinational logic circuit that subtracts two single-bit binary numbers.

It has:

- Inputs:
  - A (Minuend)
  - B (Subtrahend)

- Outputs:
  - Difference (D)
  - Borrow (Bo)

---

## Truth Table

| A | B | Difference | Borrow |
|---|---|------------|--------|
|0|0|0|0|
|0|1|1|1|
|1|0|1|0|
|1|1|0|0|

---

## Boolean Equations

Difference = A XOR B

Borrow = (~A) AND B

---

## Verilog Files

- `half_subtractor.v`
- `half_subtractor_tb.v`

---

## Simulation

The testbench checks all possible input combinations.

Expected Outputs

|A|B|Difference|Borrow|
|--|--|----------|-------|
|0|0|0|0|
|0|1|1|1|
|1|0|1|0|
|1|1|0|0|

---

## Tools Used

- Verilog HDL
- ModelSim / Vivado / Icarus Verilog
- GTKWave (optional)

---

## Author

Your Name