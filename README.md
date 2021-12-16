# CSCI596_Final_Project

## Goals
Visualize a 2d Schrodinger equation solution. More specifically an electron in a 2D well. I intend to use VisIt(https://visit-dav.github.io/visit-website/) as visualization software. 

## Reasoning
Quantum mechanics is an unintuitive field at first glance. Visualizing a simple wavefunction seemed like an interesting project that can be useful for understanding . 

## Expected results
a 3D graph(animation to describe time) of the energy (described by height) and phase (described by color) of some given wavefunction.

## Methedology
The base code that I used was taken with permission from Professor Aiichiro Nakano's PHYS 516 Course (https://aiichironakano.github.io/phys516/src/QD/, https://aiichironakano.github.io/phys516/03QD.pdf). I edited the code to print for every few timesteps the x y coordinates of a grid, the energy density at that point, and the phase. I then loaded the data into VisIt, with seperate files for each.


## Result
I used VisIt to plot the wavefunction's energy density, with the z direction representing the energy density at that point, and the color representing the phase of the wavefunction at that point. 

![alt-text](https://github.com/eshi1708/CSCI596_Final_Project/blob/main/csci596Animation.gif)

