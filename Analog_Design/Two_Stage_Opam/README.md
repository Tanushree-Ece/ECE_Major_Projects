
# Two Stage Operational Amplifier

## Overview
This project presents the design and simulation of a two-stage CMOS operational amplifier implemented in Cadence Virtuoso using UMC 28nm technology.
The objective is to analyze fundamental analog performance metrics such as gain, bandwidth, unity-gain bandwidth, and output swing.
Simulations were performed to evaluate stability, offset voltage, power supply rejection ratio (PSRR), common-mode rejection ratio (CMRR), and slew rate.

## Key Features
- Two-stage architecture with Miller compensation
- High open-loop gain
- Improved bandwidth compared to single-stage design
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
- DC Gain: [~ 78 dB]
- Phase margin: [~ 47 degree]
- unity-gain bandwidth: [38.685 MHz]
- Output Swing: [98.568 mV]

### Folder structure
 - Schematic_netlist_layout
 - Simulation
 - Images
   
## License
This project is protected under the license defined in the parent repository.
