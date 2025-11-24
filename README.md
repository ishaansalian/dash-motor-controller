# dash-motor-controller
Motor control PCB for the Dash humanoid robot project.

# 48V BLDC Motor Controller for Dash Robot

Motor control PCB for the NSF-funded Dash humanoid robot project at UIUC RoboDesign Lab.

## Specs
- 48V nominal input
- 3-phase BLDC motor control
- DRV8323 gate driver
- CAN bus communication
- Based on Ben Katz + mjbots Moteus designs

## Status
🚧 In development - schematic complete, layout in progress

## Hardware
- MCU: STM32F446
- Gate Driver: DRV8323RSRGZT
- MOSFETs: BSC030N08NS5 (80V, 3mΩ)
- Encoder: MA732GQ-Z
- CAN: MCP2542FD
