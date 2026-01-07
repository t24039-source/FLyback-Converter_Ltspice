RCD Snubber Analysis for Flyback Converter (LTspice)

This project analyzes MOSFET drain-source voltage spikes and ringing in a flyback DC-DC converter
caused by leakage inductance and device capacitances.

THe RCD snubber network is implemented and simulated in LTspice to clamp the MOSFET voltage,
reduce ringing, and lower switching stress.

Transient simulations compare MOSFET Vds waveforms with and without the snubber to demonstrate
improved switching behavior and reduced peak voltage.

RCD snubber comprises of D2 ,R3,C3 
L4 is the leakage Inductance of the circuit ,
rest other are similar to that of a flyback converter , the flyback covnerter desigend for 250W , 
images attached shows the Current and Voltage waveforms of the diode , mosfet and leakage inductance with and without snubber circuit  
Power mentioned here means power dissipated across the Mosfet 
