# System Architecture

This SCADA system was designed for a Hydrogen and Oxygen production plant
operating with two main process frames.

## Architecture Overview
- Field level: Sensors and actuators connected to PLC I/O
- Control level: Siemens S7-300 PLC
- Supervisory level: Siemens WinCC SCADA system
- Engineering level: SIMATIC STEP 7

## Communication
- PLC to SCADA communication via industrial Siemens protocols
- Real-time process data mapped through WinCC tags

## Design Philosophy
- Clear separation between production and purification processes
- Operator-friendly navigation
- Consistent alarm and trend handling
- Scalable structure for future expansion
