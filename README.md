### Spudnik Drive Mark III

<img src="https://raw.githubusercontent.com/AlSpudnik/Tube-Preamp-Fenderman/main/photo/rev32.JPG" width="400">

This is a third version tube guitar preamplifier from the Spudnik Drive series. Its design is based on the classic american amplifier. The design is positioned as a preamplifier for studio recordings and connection to a speaker simulator or power amplifier.

You can connect a guitar directly to the input of this preamplifier, as well as a processed signal - for example, a tube reverb with a classic 6G15 circuit, or its JFET clone. To add variety to overdriven amp, you can connect absolutely any booster, treble booster, overdrive pedals like the Tube Screamer, DOD 250, or even a fuzz box to the input. By manipulating the TREBLE, BASS, GAIN, PRESENCE knobs, you can achieve an endless variety of overdrive.

If you plan to use the device as a preamplifier for a power amplifier and the amplitude of the preamplifier's output signal is insufficient for you, you can reduce the value of resistor R27 to 120k, or even to 10k. As a preamplifier for a tube power amplifier, the ouput signal can be taken from the anode of tube V2b. Capacitor C9 should be connected to the anode of tube V2b, and potentiometer R28 should be changed to 250...500k. In this case, capacitor C10 must be excluded from the circuit. With this connection, the output signal will have a higher impedance.

<b>Design and components:</b>
<br />
Please note in the diagram, I did use soviet 6N2P (6Н2П). You can use any analogs, such as ECC83, 7025, 5751, or 12AX7 (take note pinout!). In this circuit, 6N2P tubes operate at a lower anode voltage. This, too, is up to you to decide how close to the original Showman voltage you want it to be.

The ratings of resistors R12, R14 which are indicated in parentheses, are an imitation version of the Bassman 6G6-B.

Since I assembled the physical design in the same case as the previous version (<a href="https://mrspudnik.blogspot.com/2020/09/spudnik-drive-mark-ii.html" target="_blank" >Spudnik Drive mk II</a>), the BASS and PRESENCE potentiometers are designed as trimmers. But the layout is standard on the front panel.

The main part of the applied MLT (МЛТ) resistors is metal film. Carbon resistors of the VS (BC) series are used as R12, R17.

Between stages, use high-quality film capacitors with a rated voltage of at least 400 volts (with an increase in anode voltage to the Fender level, capacitors are 630 volts). For C2, C3, C4, C10 I used Evox Rifa MMK Metal Film. For C5, C6, C11 used soviet KSO (КСО). For С8, C9 soviet K73. For C1, C7 Nichicon 50V BP.

As can be seen in the diagram, the lamp preheating is turned on immediately when the device is connected to the network, and the switch of the IEC320 AC-17 socket is connected as Standby.

The power transformer must have a shielding layer between the mains winding and the anode winding. Or the filament winding—with a center tap connected to ground—should be wound between them.

### Parts List:
<b>Resistors</b>
<br />
R1, R16, R22 = 1M (0,25W)
<br />
R2 = 30k (0,25W)
<br />
R3, R12, R24 = 100k (0,5W)
<br />
R4 = 1.5k (0,5W)
<br />
R5, R9 = 100k (0,25W)
<br />
R7 = 6.8k (0,25W)
<br />
R11, R21 = 15k (0,25W)
<br />
R13 = 2.7M (0,25W)
<br />
R14 = 820 Ohm (0,5W)
<br />
R15 = 120k (0,25W)
<br />

<b>Potentiometers</b>
<br />
R6, R8 = A250k (logarithmic)
<br />
R10, R32 = B1M (dual-gang linear)
<br />
R20 = B20k (linear)
<br />
R28 = A100k (logarithmic)
<br />

<b>Capacitors</b>
<br />
C1, C7 = 22µF 22V (Electrolitic)
<br />
C2, C11 = 270pF 400V (Metal Film)
<br />
C3, C10 = 100nF 400V (Metal Film)
<br />
C4 = 47nF 400V (Metal Film)
<br />
C5 = 2.2nF 400V (Metal Film)
<br />
C6 = 1nF 400V (Metal Film)
<br />
C8 = 4.7nF 400V (Metal Film)
<br />
C9 = 100nF 250V (Metal Film)
<br />
C12 = 1.5nF 630VAC (Polypropylene Film)
<br />
C13 = 47nF 400V (General Purpose Film Metallized Polypropylene)
<br />
C14, C16, C18 = 47µF 400V (Electrolitic)
<br />
C15, C17 = 33nF 400V (General Purpose Film Metallized Polypropylene)
<br />
C19 = 22µF 400V (Electrolitic)
<br />

<b>Diodes</b>
<br />
D1 - 1N4007 or another
<br />
D2, D3 - 3mm LED
<br />
Rectifier MB10F
<br />

<b>Tubes</b>
<br />
V1, V2 - 6N2P
<br />
Two nine-pin tube sockets
<br />

<b>Sockets</b>
<br />
Two jack sockets 6.35mm female with switch
<br />
Power socket IEC320 AC-17
<br />

<b>Power Transformer</b>
<br />
Power 15...20W. Anode winding = 200...210v AC, 10mA minimal. Filament winding = 6.6v AC, 0.8A.

<b>Filter Choke</b>
<br />
Inductance = 0.17 Henry
Current = 10mA
