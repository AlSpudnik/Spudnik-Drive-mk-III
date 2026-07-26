### Spudnik Drive Mark III "Fenderman"

<img src="https://raw.githubusercontent.com/AlSpudnik/Tube-Preamp-Fenderman/main/photo/rev32.JPG" width="400">

Fenderman this is a third version tube guitar preamplifier from the Spudnik Drive series. Its design is based on the classic Fender Showman amplifier. The device does not claim to be an exact emulator of the Fender Showman, but rather one of the options for imitating these amplifiers. The design is positioned as a preamplifier for studio recordings and connection to a speaker simulator or power amplifier.

You can connect a guitar directly to the input of this preamplifier, as well as a processed signal - for example, a tube reverb with a classic 6G15 circuit, or its JFET clone. To add variety to overdriven amp, you can connect absolutely any booster, treble booster, overdrive pedals like the Tube Screamer, DOD 250, or even a fuzz box to the input. By manipulating the TREBLE, BASS, GAIN, PRESENCE knobs, you can achieve an endless variety of overdrive.

Please note in the diagram, I did use soviet 6N2P (6Н2П) tubs instead 7025 (used in Showman 6G14). You can use any analogs, such as ECC83, 5751, or 12AX7 (take note pinout!). In this circuit, 6N2P tubes operate at a lower anode voltage. This, too, is up to you to decide how close to the original Showman voltage you want it to be.

If you plan to use the device as a preamplifier for a power amplifier and the amplitude of the preamplifier's output signal is insufficient for you, you can reduce the value of resistor R27 to 120k, or even to 10k. As a preamplifier for a tube power amplifier, the ouput signal can be taken from the anode of tube V2b. Capacitor C9 should be connected to the anode of tube V2b, and potentiometer R28 should be changed to 250...500k. In this case, capacitor C10 must be excluded from the circuit. With this connection, the output signal will have a higher impedance.

<b>Design and components:</b>
<br />
Since I assembled the physical design in the same case as the previous version (<a href="https://mrspudnik.blogspot.com/2020/09/spudnik-drive-mark-ii.html" target="_blank" >Spudnik Drive mk II</a>), the BASS and PRESENCE potentiometers are designed as trimmers. But the layout is standard on the front panel.

The main part of the applied MLT (МЛТ) resistors is metal film. Carbon resistors of the VS (BC) series are used as R12, R17.

Between stages, use high-quality film capacitors with a rated voltage of at least 400 volts (with an increase in anode voltage to the Fender level, capacitors are 680 volts). For C2, C3, C4, C9 I used Evox Rifa MMK Metal Film. For C5, C6, C10 used soviet KSO (КСО). For С7, C8 soviet K73. For C1, C7 Nichicon 50V BP.

As can be seen in the diagram, the lamp preheating is turned on immediately when the device is connected to the network, and the switch of the IEC320 AC-17 socket is connected as Standby.

The power transformer must have a shielding layer between the mains winding and the anode winding. Or the filament winding—with a center tap connected to ground—should be wound between them.

### Parts List:
<b>Resistors</b>

<b>Potentiometers</b>
<br />



<b>Capacitors</b>
<br />
C1= 22µF 22V (electro)
<br />
C2 = 270pF 400V (film)
<br />
C1 = 200nF 63V (film or polarized electro)
<br />


<b>Diodes</b>
<br />

<b>Tubes</b>
<br />
V1, V2 - 6N2P
<br />
Two nine-pin tube sockets

<b>Power Socket</b>
<br />
IEC320 AC-17

<b>Power Transformer</b>
<br />
6W minimal. Anode winding = 206v AC, 10mA. Filament winding = 6.6...6.8v AC, 0.8A.

<b>Filter Choke</b>
<br />
Inductance = 0.17 Henry, 10mA.
