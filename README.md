## 2to4_priority_encoder
Verilog implementation and functional verification of 2:4 priority encoder using a testbench and simulation waveform

## Overview

This project implements a **4:2 Priority Encoder** in Verilog HDL. A priority encoder converts multiple input lines into a 2-bit binary code by selecting the **highest-priority active input**.

Unlike a normal encoder, if multiple inputs are HIGH simultaneously, the encoder gives priority to the highest-order input.

### Priority Order

D3 > D2 > D1 > D0

# Inputs and Outputs

## Inputs

| Signal | Width | Description |
|--------|-------|-------------|
| d | 4-bit | Input lines (d[3:0]) |

## Outputs

| Signal | Width | Description |
|--------|-------|-------------|
| y | 2-bit | Encoded binary output |
| valid | 1-bit | Indicates whether at least one input is HIGH |
