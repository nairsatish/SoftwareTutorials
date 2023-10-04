# SoftwareTutorials
These are tutorials made either for the CS 4590 course or for the Neural Modeling manual later on.


For B3:
make spike recorder at end node and first node and subtract the time values to get speed of ap time
To simulate without myelin sheath: do the same thing but make gl be divided by 10 instead, and put in the commented values for the the active channels

For Dendrite_Length_Constant:
Add back in axial and leak current.
add axial currents back then, and show how the leak current decays as well 
show the stuff about the current going from left to right
axial coming in - axial coming out = leak current

add the individual segments in again, and limit the x-axis and title it Transience in Voltage(takes some time)
have it graph every 50 time steps of the voltage since only the max voltage at the end is shown. why is not instant(some has to charge the capacitor beforehand before it starts leaking out)
make the questions
talk about what the length constant is good for(checking if)

in myelinated segments, have gna = gk = gleak = 0
after a spike in the soma
voltage will linearly drop within the myelinated segments. Ideally there'd be enough current to cause the gna channels inbetween the myelinated segments to then spike and cause it go again down the axon.

have voltage start higher by increasing axon hillock conductance
