# SoftwareTutorials
These are tutorials made either for the CS 4590 course or for the Neural Modeling manual later on.


For B3:
make spike recorder at end node and first node and subtract the time values to get speed of ap time
To simulate without myelin sheath: do the same thing but make gl be divided by 10 instead, and put in the commented values for the the active channels
in myelinated segments, have gna = gk = gleak = 0
after a spike in the soma
voltage will linearly drop within the myelinated segments. Ideally there'd be enough current to cause the gna channels inbetween the myelinated segments to then spike and cause it go again down the axon.

have voltage start higher by increasing axon hillock conductance
For B2:
add the individual segments in again, and limit the x-axis and title it Transience in Voltage(takes some time) Take that from:
https://github.com/davidfague/Computational-Neuroscience-tutorials/blob/main/B2_CableTheory.ipynb
Graph Voltage over distance every 50 times steps to show how it is not instant(some has to go to charge the capacitor before it starts leaking). 
have it graph every 50 time steps of the voltage since only the max voltage at the end is shown. why is not instant(some has to charge the capacitor beforehand before it starts leaking out)
Add questions about how the length constant changes in response to different things(like membrane resistance, axial resistivity, and diameter)


