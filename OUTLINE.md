# Project Outline

### Summary
-----------
File for outlining future steps in project, along with past steps and completed steps from previous outlines.

### Project Coding Plan

#### To be completed for 04.27.2020:
-Have a working Jupyter notebook.
-Create a function magnetizationDueToTemp to generate two arrays of data, one for the magnetization of a metal and the other to be the temperature of the metal.
-Have preliminary steps for code of the Ising model.
-Call magnetizationDueToTemp for iron and create plot.

#### To be completed for 05.01.2020:
-complete function magnetizationDueToTemp. The inputted constants are the magnetic moment $\muy$, a coupling constant $J$, and Boltzmann's constant $k_B$. This function will take these constants in as inputs, along with an initial temperature value and magnetism. The function will ouptu two arrays: one for magnetization strength values and the other for temperature values, respective to the magnetization strength array. When plotted with respect to one another, these arrays should show the material losing magnetism as temperature increases and a sudden transition to where the magnetization strength is zero. This point is the curie point.
-have Ising model fully functional and be able to change constants using sliders. Test for accuracy by increasing temperature constant, this should increase the number of state changes that occur. At decreased temperatures would expect a more stable state where there are uniform state areas within the model.
