# Basys3 Digital Logic Design (VHDL / Verilog)

FPGA digital logic projects targeting the Digilent **Basys3** board, built with **Xilinx Vivado**.  
This repo is organized into modules/labs, each containing a focused project with the Vivado project file plus key source/artifact files (VHDL/Verilog, constraints, bitstreams, etc.).



## Tools / Platform
- **Board:** Digilent Basys3 (Artix-7)
- **Toolchain:** Xilinx Vivado
- **Languages:** VHDL / Verilog (plus Vivado block design artifacts)



## Modules

### `Basys3-Digital-Logic-Foundations`
Foundational Basys3 projects covering core digital logic workflows:

- **`Two-to-One-Multiplexer-VHDL`**  
  Implements a 2:1 multiplexer design in VHDL, including constraints and build artifacts.

- **`Vivado-Block-Design-Integration`**  
  Demonstrates creating/integrating a design using Vivado’s block design flow and generated wrappers.

- **`Multi-Module-Digital-System`**  
  A structured, multi-file digital system demonstrating modular design organization for FPGA projects.

> Each folder contains a Vivado project (`.xpr`) and the key sources/artifacts needed to open/build the project in Vivado.



## How to Run (Vivado)
1. Open Vivado
2. **File → Open Project** and select the `.xpr` inside the project folder
3. (If needed) confirm the constraints file (`.xdc`) is included
4. **Generate Bitstream**
5. **Open Hardware Manager → Program Device** to load the `.bit` file onto the Basys3



## Notes
- Some projects include generated files (wrappers, block design exports, bitstreams) to make it easier to reproduce results.
- If you only want the “clean source,” keep the HDL + `.xdc` + `.xpr` and remove large generated folders as needed.

