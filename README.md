# SteampunkTouchLamp (In Progress)

![alt text](https://github.com/tylerpleiter/SteampunkTouchLamp/blob/master/BuildImages/05_Lamp-Assembled.jpg "Steampunk Touch Lamp")

## Description:

A steampunk inspired touch lamp with a glass center chamber filled with oil, bubbles and an LED. Touch sensitive copper bars turn the lamp from OFF->LED->Main_Globe->OFF. Bubbles are controled using red tap valve connected to rotary encoder. 

## Progress:

Started roughly November 2019 with sporadic contributions until now. PCB ordered and recently delivered (June 2020), parts soldered and wires connected. Some preliminary functionality testing of wiring indicate lamp functions as expected. 

### Todo
- Thorough testing of touch sensitivity and high voltage isolation
- Fit PCB into base - may need space chiseled out to fit in gap
- Clean up staining, woodfilling
- Paint E27 light bracked
- Fill with semi-transparent black fluid - possibly used car engine oil
- Test bubbler
- Seal glass tube to prevent oil leakage

## Issues:

- Initial schematic and PCB design failed due to layout. MOSFETs setup with low-side switching resulting in them unable to turn on LED or relay. Re-designed for high-side switching. PCB re-ordered, assembled and testing indicate problem resolved.
- Difficulty attaching Flip-Flop IC (U2) to PCB due to slightly under-sized footprint, resulted in unattached GND pin leading to floating voltages preventing proper switching. Problem found and resolved on existing PCB through creative soldering.

## Improvements:

- Redesign circuit to turn from LED->OFF if LED activated for longer than set time, preventing brighter main globe from blinding user at night.
