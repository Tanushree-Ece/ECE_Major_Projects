# Single Stage Operational Amplifier

## Overview
This project presents the design and simulation of a single-stage CMOS operational amplifier at the transistor level.  
The objective is to analyze fundamental analog performance metrics such as gain, bandwidth, unity-gain bandwidth, and output swing.
Simulations were performed to evaluate stability, offset voltage, power supply rejection ratio (PSRR), common-mode rejection ratio (CMRR), and slew rate.

## Design Description
- Single-stage amplifier using CMOS transistors
- Proper biasing to ensure operation in saturation and sub-threshold region

## Tools & Technology
- Tool: Cadence Virtuoso
- Simulator: Spectre
- Technology: UMC 28nm 

## Simulations Performed
- DC Analysis: Bias point verification
- AC Analysis: Gain and bandwidth estimation
- Transient Analysis: Time-domain response


## Key Performance Parameters
- DC Gain: [~ 40 dB]
- Phase margin: [~ 87 degree]
- unity-gain bandwidth: [7.075 MHz]
- Output Swing: [99.204 mV]

### Folder structure
 - Schematic_netlist_layout
 - Simulation
 - Images






## Notes
- Transistor sizing chosen to meet gain and power constraints
- Design focuses on understanding core analog trade-offs

