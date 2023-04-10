Concepts
==================================

Generators
----------------------------------

Ramp Generator
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

A ramp generator is a waveform generator which produces analog waveforms synchronous to the horizontal or vertical dimensions of the video screen.  It is a common component of analog graphics modules, such as shape and pattern generators.

Voltage Controlled Oscillator (VCO)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

A voltage controlled oscillator is similar to a ramp generator, only its frequency may be changed or modulated.  A voltage controlled oscillator may be free running, or reset in time with the video sync to synthesize a stable pattern.

Frame Synchronizer
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

A frame synchronizer takes an external video feed and synchronizes it with the system's internal timing.  A frame synchronizer is usually required to input multiple external video sources into your system like cameras and media players.

Functions
----------------------------------

Modules often contain many analog functions.  Some modules may have similar internal function blocks, but different strategies for allowing the user access to them. 

Comparator 
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Also known as a hard key generator or 1-bit ADC (Analog-to-Digital converter) function. When the positive input voltage is greater than the negative input voltage, the output is 1 volt (White Level).  Otherwise, the output is 0 volts (Black Level).

Clipping Amplifier
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Also known as a soft key generator or wide range contrast processor.  The output is created by amplifying the video source to create a high contrast mask with variable edge width.

Encoder
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

A video encoder takes 1 volt scale unipolar signals for Red, Green & Blue color channels, and performs all operations required to convert them into a video signal for display or recording.

Negative 
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Also known as a voltage mirror.  The output is equal to the input voltage is subtracted from 1 volt (White Level).

Doubler
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Also known as a saw-to-triangle waveshaper, the doubler is a combination of an absolute value function and clipping amplifier function.

Logarithmic Amplifier
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

An logarithmic amplifier changes a linear input voltage into an output with logarithmic scale.

Exponential Amplifier
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

An exponential amplifier changes a linear input voltage into an output with exponential scale.

Summing Amplifier
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Also known as a Mixer.  A summing amplifier adds two or more voltages to each other. The voltages may be unipolar or bipolar scale.

Minimum Value
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

A minimum value function compares two or more inputs, and passes the input with the least voltage to the output.

Maximum Value
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

A maximum value function compares two or more inputs, and passes the input with the most voltage to the output.

Absolute Value 
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

An absolute value function inverts all values below zero and forces the output to be positive.







