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
![Screenshot 2024-11-23 000200](https://github.com/user-attachments/assets/b4491aab-ea83-4781-8ab1-a3c8812830ab)

#### Area report:
![Screenshot 2024-11-24 215831](https://github.com/user-attachments/assets/c7ff76b3-5b59-44ba-a7fb-a3aa06d513ca)

#### Power Report:
![Screenshot 2024-11-24 215751](https://github.com/user-attachments/assets/86dc0322-a848-4649-9ce8-d57c6d94f3b9)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
