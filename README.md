# Automatic Box Sorting System - FactoryIO + CODESYS

This repository contains the simulation and control code for an automatic box sorting system developed using **Factory I/O** and **CODESYS**.

## Description

The system simulates an automated sorting line where boxes are sorted by size using industrial automation logic. The integration between Factory I/O and CODESYS enables real-time control of the sorting process.

- **Factory I/O** is used to model and simulate the physical environment (conveyors, sensors, actuators, boxes, etc.).
- **CODESYS** is used to develop the PLC control logic for sorting.

> ⚠ This repository contains only the project files and simulation models.  
> No academic paper or full report is included.

## Contents

- `/FactoryIO` — Factory I/O project file (`.factoryio`)
- `/CODESYS` — CODESYS project file (`.project`)

## Usage

1. Open the Factory I/O file in Factory I/O (version 2.4.3).
2. Open the CODESYS project (version 3.5 SP16).
3. Establish the connection between Factory I/O and CODESYS (via Modbus TCP/IP protocol).
4. Run the simulation and control system.

