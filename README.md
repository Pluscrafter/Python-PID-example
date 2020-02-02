# Python-PID-example
An very small example to explain an PID regulator wite in python.

## Dependencies
- mathplotlib
- numpy

Install the dependencies, if not installed yet via pip:
    
    python -m pip install -U matplotlib
    python -m pip install -U numpy
    
## Usage
Just move the sliders and look how the PID regulator, regulates the actual value(Istwert) to the setpoint value. If you want to change the setpoint curve, change the "Sollwert" list. 

## Bugs
Plot isn't visible after start. You must move one of the sliders to show the plot.

## Thanks
Thanks to [Stephan Müller's video](https://www.youtube.com/watch?v=dPkFMeiUni4) explaining the PID regulator with an excel sheet for inspiring to write this small script.
