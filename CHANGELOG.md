# Changelog

## V0.1 

- First prototype

## V0.2

- Add 3.3V onboard reg 
- Change AC-DC PSU, add multiple footprints 
- Add mounting holes 
- Add protection varistors 

## V0.3

- Move C6 to be closer to input of 3.3V vreg 
- Fix silkscreen labels, move all text to TNames 
- Increase footprint size of C5 to case C
- Fix footprint for input AC connections 
- Fix position of R34 current limiting resistor
- Increase size of holes for J3 

## V0.4

- Reduce TVS MOV to 14mm disk footprint 
- Move J9 and J2 to give more clearance for glands
- Reduce board size to 77mm x 100mm
- Fix footprint for MP-LD10-23B05R2 10W PSU
- Add fiducials, RoHs & OSHW logos 

## V0.5

- Increase board size to fit new case
- Invert voltage sample polarity 
- common-mode choke filter and capacitor 
- Add AC GND connection 
- Increase input connection clearance 
- Add footprint for smaller X2 capacitors 

## V0.6

- Move voltage sense voltage dividers from emonVS to emonTx 

## V0.7

- GND > E
- Move to using screw terminals for AC connection due to component shortages :-(
- Tent vias 

## V1.0

- Tidy up and bump version for production 
- Silkscreen and clearance improvements


## V1.1

- Fix milling 
- V1.1 rev2: minor silkscreen and pad size tweaks for production


## V1.2

- Signal and power output connector changed from RJ11 to RJ45.


## V1.3

- General improvements to schematic symbols organization and aesthetics.
- Phase L1 MOV removed from the output choke (L1) and placed on the input.
  In this way, protecting the cooke input capacitor and building a classic "common mode surge suppression" topology.
