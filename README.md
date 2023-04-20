# Tesla Model S Trailer Wiring Adapter
A typical way to add trailer wiring to any vehicle is to tap the
rear turn signal wires and one taillight wire as input to a trailer wiring module.
Unfortunately, on a Tesla Model S the taillights flash with the turn
signals if the taillights are otherswise off. So if you tap, say, the
left taillight, then all the parking lights flash on the trailer
when the left turn signal is used.

Ideally, this problem could be solved by tapping the license plate
light wire. However, that wire is in the passenger-side C-pillar and is difficult
to access compared to the taillights. This device solves the problem
by using a tap on *both* taillights, requiring both to be on for the
wiring module to enable the trailer parking lights.

**IMPORTANT!** This device is not designed the drive the trailer lights
directly. It must be connected to a trailer wiring module.

![Device Installed](https://raw.githubusercontent.com/TimPaterson/Tesla-Trailer-Wiring-Adapter/master/Images/Installed.jpg)
![Enclosed](https://raw.githubusercontent.com/TimPaterson/Tesla-Trailer-Wiring-Adapter/master/Images/Enclosed.jpg)

![PCB](https://raw.githubusercontent.com/TimPaterson/Tesla-Trailer-Wiring-Adapter/master/Images/PCB.jpg)
![Schematic](https://raw.githubusercontent.com/TimPaterson/Tesla-Trailer-Wiring-Adapter/master/Images/Schematic.png)

### Building It
Total parts cost for the device is around $5, not including shipping.
Here is the parts list:

|Qty|Component          |Source    |Part No.|
|---|---------          |------    |--------|
| 1 |DMC3025LSD, SOIC   |Digi-Key  |DMC3025LSD-13DICT-ND|
| 2 |47k resistor, 0603 |Digi-Key  |A129708CT-ND|
| 4 |#6 ring terminal   |Digi-Key  |A1060-ND|
|   |alternate for above|Home Depot|283218|
| 4 |#6-32 x 1/4" screw |Home Depot|766276|
| 4 |#6-32 lock nut     |Home Depot|321541|
| 1 |PCB                |OSH Park  |[https://oshpark.com/shared_projects/NLgesyix](https://oshpark.com/shared_projects/NLgesyix)|

Assembling this project requires soldering surface-mount devices (SMDs),
but they are as big as SMDs get and should be doable even for a first-timer.
Before assembling, file the nubs off the sides of the PCB so it will fit
in the enclosure.

An enclosure design is included in STL format for 3D printing. It's Fusion 360 design
file is also included.

### Connecting It
The two terminals on the left side, labeled "IN", connect to taps on the left
and right taillight wires. The terminal labeled "OUT" connects to the trailer
wiring module parking light input. The terminal labeled "GND" must be connected to the chassis,
probably at the same point as the trailer wiring module.

### Buying an Assembled Unit
If it's worth $30 to you to buy one assembled, express your interest in a discussion. 