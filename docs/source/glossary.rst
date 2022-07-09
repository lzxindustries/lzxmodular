Glossary
====================

key 
    any video signal used to control a transition between two or more other video signals
    
hard key
    a boolean logic signal which switches between two signals.

key generator
    a module designed to condition an input for the purpose of keying operations

soft key
    an analog voltage representing the mix ratio between two video signals

hard key generator
    typically implemented as a differential analog comparator.

soft key generator
    typically implemented as a high gain differential amplifier with black and white level clipping
    
chroma key generator
    processes the chroma components (PbPr) of a component video signal, allowing key extraction based on Hue and Saturation of the video source

luma key generator
    processes the luma component (Y) of a component video signal, allowing key extraction based on the overall brightness of the video source

multi level key generator
    produces multiple key signals from a single source, and are often used as the frontend for colorizers and sequencers
    
component key generator 
    acts on one color channel at a time, but still includes the entire colorspace in its output function

window key generator 
    has dual threshold controls, either Upper/Lower or Span/Center

fader
    a module which performs a transition between two video sources. typically it has a direct key input, without much local control over the key itself.
    
keyer 
    a module which has both a key generator and a fader or switcher
    
linear colorizer / multi level keyer 
    combines multiple faders with a multi level key generator function to produce a transition across more than two inputs
