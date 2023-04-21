# emonVS (Voltage Sense Power Supply)

Three phase AC Voltage Sensor and Power Supply for emonTx V4 / emonPi V2

![emonVS.jpg](emonVS.jpg)

# RJ11 

The RJ11 connector is used to connect the AC voltage sensor output to the emonTx V4, the emonTx V4 / emonPi V2 are also powered by the RJ11 connector. 

*Note: It's essential to use a 6P6C (6-pin, 6-connected) RJ11 cable, many telephone RJ11 cables only 6P4C (only 4-pins connected)*

## Pinout

1. GND
2. 5V
3. BIAS or 3.3V (if jumper SJ1 closed)
4. VS3
5. VS2
6. VS1 


# 5V Output

An emonBase can be powered using a open-ended USB-C connector wired into the 5V output terminals.

**Max: 5V 2A**

## Schematic Preview 
<p align="center"><a href="1.3/emonVS.pdf"><img src="1.3/assets/schematic_preview.png"  title="Schematic Preview" alt="PDF Download"></a></p>

## Bill of Materials
| Qty | Designator | Description | PN |
|--|--|--|--|
1	|C1|	1uF x 16V|	GCM188R71C105KA64D| 
1	|C2|	180uF x 6.3V|	6SVPE180M|
1	|C3|	1uF x 310VAC|	B32923C3105M000|
1	|CN1|	Terminal block, 5 pins, 5 mm pitch|	282836-5|
1	|CN3|	Terminal block, 2 pins, 5 mm pitch|	282836-2|
1	|CN2|	RJ45 Jack|	PRT-00643|
1	|D1|	TVS diode|	SMBJ7.0A|
3	|F1, F2, F3|	Slow blow fuse, 1A X 250V|	MST 1A 250V|
1	|L1|	Common Mode Choke, 47mH|	RN214-0.3-02-47M|
1	|L2|	Common Mode Choke, 100uH|	744252101|
1	|PS1|	AC-DC converter, 5W / 5V|	MP-LD10-23B05R2|
18	|R1, R2, R3, R5, R6, R7, R8, R9, R10, R12, R13, R14, R15, R16, R17, R19, R20, R21|	10k (5%)|	ERJ-H3GJ103V|
3	|R4, R11, R18|	75R (1%)|	ERJ-H3EF75R0V|
3	|RV1, RV2, RV3|	Varistor, 275VAC|	MOV-14D431KTR|
3	|T1, T2, T3|	Micro-transformer, 1000:1000 ratio|	ZMPT101B|

3D Model Preview
<p align="center"><a href="1.3/assets/emonVS%20v1.3.step"><img src="1.3/assets/3d_model_preview.PNG"  title="3D model file" alt=".STEP Download"></a></p>



