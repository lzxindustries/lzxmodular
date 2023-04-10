Electrical
============================

LZX Modular proposes an interface specification for wide bandwidth analog computing instruments. It is optimized for, but not limited to: (1) generating and processing analog RGB video graphics in SD/HD resolutions, (2) affordable devices which are accessible to working artists and not just big studios, and (3) maximum patchability via a universal DC voltage range and high impedance connections.

Patchable Signals
----------------------

Waveform generators, video sources, boolean logic, and control voltages all share the same voltage ranges and IO connectors.  Cross patching different signal types is an encouraged use of the system.  

:Connectors: 3.5mm mono jacks 
:Cables: 3.5mm patch cables
:Unipolar Scale: 0 to +1V DC
:Bipolar Scale: +/-1V DC
:Minimum Bandwidth: 10 MHz
:Input Impedance: 100K ohms

Video
^^^^^^^^^^^^^^^^^^^^^

0 IRE (Black Level) and 100 IRE (White Level) are scaled to the patchable unipolar range.

Logic
^^^^^^^^^^^^^^^^^^^^^

Inputs to logic gates, multiplexer controls, and other CMOS functions must have an analog voltage comparator frontend, for converting any voltage into a binary signal. 

:Comparator Threshold: 0.5V DC
