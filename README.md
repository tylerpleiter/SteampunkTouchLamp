# SteampunkTouchLamp (In Progress)

## Description:

A steampunk inspired touch lamp. 

## Progress:

Started roughly November 2019 with sporadic contributions until now. PCB ordered and recently delivered (June 2020), parts soldered and wires connected. Some preliminary functionality testing of wiring indicate lamp functions as expected. 

## Issues:

- Initial schematic and PCB design failed due to layout. MOSFETs setup with low-side switching resulting in them unable to turn on LED or relay. Re-designed for high-side switching. PCB re-ordered, assembled and testing indicate problem resolved.
- Difficulty attaching Flip-Flop IC (U2) to PCB due to slightly under-sized footprint, resulted in unattached GND pin leading to floating voltages preventing proper switching. Problem found and resolved on existing PCB through creative soldering.
