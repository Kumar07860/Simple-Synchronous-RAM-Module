# Simple-Synchronous-RAM-Module

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : REDDY HEMANTH KUMAR

*INTERN ID* : CTIS3666

*DOMAIN* : VLSI

*DURATION* : 6 MONTHS

*MENTOR* : NEELA SANTHOSH KUMAR

*DESCRIPTION* :
                # Simple Synchronous RAM Module – VHDL

## Project Overview
This project implements a Simple Synchronous RAM Module using VHDL.  
The design supports synchronous read and write operations and is verified using a VHDL testbench and ModelSim simulation.

## Features
- 8 x 8-bit memory locations  
- Synchronous read and write operations  
- Clock-based operation  
- Write enable control  
- Fully verified using simulation  

## Project Files

The repository contains the following files:

1. sync_ram.vhd  
   - VHDL design code for synchronous RAM module

2. sync_ram_tb.vhd  
   - VHDL testbench used to verify RAM functionality

3. Simulation Output Screenshots  
   - Demonstrates correct read and write operations

## Design Description

The RAM module contains:
- 3-bit address input (8 locations)
- 8-bit data input
- 8-bit data output
- Write Enable (we) signal
- Clock signal

Write operation occurs when:
we = '1' on rising edge of clock

Read operation occurs on every rising edge of clock.

## Simulation Tool Used

- ModelSim – Intel FPGA Starter Edition 2020.1

## Simulation Procedure

1. Compile the VHDL files  
2. Load the testbench  
3. Run the simulation  
4. Observe waveforms  
5. Verify correct read and write operations  

## Expected Functionality

Data written to specific addresses is correctly read back when write enable is disabled.

Example:

Address 000 → Data 11  
Address 001 → Data 22  
Address 010 → Data 33  
Address 011 → Data 44  

## Result

The simulation results confirm that the synchronous RAM module functions correctly for both read and write operations.

## Author

Created as part of Digital System Design laboratory work.

*OUTPUT* :

<img width="1920" height="1021" alt="Image" src="https://github.com/user-attachments/assets/8ba787b5-7cfe-47e1-8e8f-1b93a4ce3bbb" />

<img width="1920" height="1022" alt="Image" src="https://github.com/user-attachments/assets/28028bbb-cdf6-4671-92f6-36f0b91700ec" />

