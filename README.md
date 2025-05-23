# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :
![WhatsApp Image 2025-05-20 at 18 17 55_9a235804](https://github.com/user-attachments/assets/580b135d-90fa-436a-9867-87feefa288b5)

#### Area report:
![WhatsApp Image 2025-05-20 at 18 17 54_26f476ec](https://github.com/user-attachments/assets/8a765996-3563-4f80-a35b-2a1001840266)

#### Power Report:
![WhatsApp Image 2025-05-20 at 18 17 55_0b8d9cda](https://github.com/user-attachments/assets/f6c51c3f-7484-4ac3-98d0-1eb38f4107a8)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
