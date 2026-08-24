# Hi, I'm Kelvin

I'm a Computer Engineering student interested in computer architecture, digital design, embedded systems, and hardware-software integration.

Right now, I'm especially focused on building projects that show how systems work under the hood, from pipelined processors and cache behavior to embedded firmware, sensor interfaces, and real-time hardware-software communication.

## What I'm Working On

- Building and simulating digital systems in Verilog
- Exploring pipelining, hazard detection, forwarding, and cache integration in a RISC-V processor
- Developing embedded firmware for sensor-based systems using low-level drivers and board bring-up
- Testing designs in simulation and on hardware
- Strengthening the software side of hardware projects with scripts, tooling, and data workflows

## Featured Project Areas

- RISC-V pipelined processor design in Verilog
- FPGA implementation and Quartus-based validation
- Cache and memory hierarchy experiments
- Embedded firmware for physiological sensing and IMU integration
- Low-level tooling such as assembly workflows, debugging utilities, and data visualization

## Selected Projects

### RISC-V Pipelined Processor

A 5-stage RISC-V processor built in Verilog with forwarding, hazard handling, control-flow flushing, and a blocking cache backed by a slower memory model.

Highlights:

- Designed and simulated a pipelined processor datapath and control path
- Implemented hazard detection, forwarding, and pipeline flushing
- Added a cache layer and tested miss behavior with pipeline stalls
- Wrote a Python-based assembler flow to generate machine-code memory files
- Validated the design in simulation and on FPGA hardware using Quartus and instantiated RAM

Repository:

- [RISCV-Pipelined-Processor](https://github.com/kelvinopoku777/RISCV-Pipelined-Processor)

### PPG Monitoring Device Firmware

Firmware development for a wearable-style PPG monitoring system using Zephyr RTOS, BLE, optical front-end sensors, and an IMU.

Highlights:

- Worked on firmware integration for an LSM6DSOTR IMU alongside existing MAX86141-based PPG sensing firmware
- Read and analyzed low-level sensor initialization and register configuration to understand driver behavior
- Implemented accelerometer and gyroscope data paths for BLE transmission and browser-based visualization
- Debugged real hardware bring-up issues involving I2C addressing, pin mapping, power sequencing, and sensor readiness
- Built and adjusted a web view for live sensor monitoring and improved the data handling flow for streamed measurements
- Used iterative logging, register-level reasoning, and firmware testing to isolate sensor communication and initialization issues

Repository:

- [PPG-Monitor (collaborative repo)](https://github.com/10dojak/PPG-Monitor)

### 16-Bit Processor (Transistor-Level CMOS, Collaborative Project)

A collaborative chip-design project centered on building a 16-bit RISC processor at the transistor level, from schematic capture through physical layout and mixed-signal verification.

Highlights:

- Contributed to a five-member team designing a 16-bit processor at the transistor level
- Built transistor-level schematics in Xschem and physical layouts in KLayout using the GF180 MCU PDK
- Performed verification through DRC/LVS and evaluated post-layout timing with parasitic-extracted netlists
- Integrated transistor-level hardware with Verilog models of the control unit, instruction memory, and data memory for mixed-signal simulation
- Verified execution with arithmetic, branching, memory, shifting, jump-and-link, and iterative Fibonacci test programs

Repository:

- [engn1600-team1 (collaborative repo)](https://github.com/mgyee/engn1600-team1)


## What I Like Building

- Projects that connect theory from computer architecture to something testable
- Designs where I can reason through correctness using waveforms, timing, logs, and hardware behavior
- Systems that involve both hardware-facing code and supporting software tools
- Projects that combine embedded firmware, communication interfaces, and real-time data flow

## Currently Learning

- Stronger FPGA system integration
- More polished verification and testing workflows
- Embedded sensor bring-up and driver development
- Better ways to present technical projects clearly for recruiters and engineers

## Connect

- GitHub: [kelvinopoku777](https://github.com/kelvinopoku777)
- LinkedIn: www.linkedin.com/in/kelvin-opoku-1267a028a
- Email: kelvin_amankwaa@brown.edu

