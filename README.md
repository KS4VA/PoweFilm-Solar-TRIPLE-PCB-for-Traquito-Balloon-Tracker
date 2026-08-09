# PowerFilm Solar TRIPLE PCB for Traquito balloon tracker
A PCB spreader to mount three vertical low sun angle PowerFilm MPT3.6-150 solar cells to a Traquito pico balloon tracker

## Features
* Achieve low angle sun performance down to 2 degrees above the horizon
* Neatly mount a robust flexible plastic solar cell array to a Traquito, with no wires
* Tough enough to be handled by a child or dragged on the ground in a botched launch (ask me how I know)
* Light weight when fabricated as a 0.8 mm thick PCB
* Makes a great beginner PCB project - create your first custom PCB by using KiCAD's free PCB software and figuring out how to change "KS4VA" to your own call sign in the silkscreen layers
* Extremely low cost (i.e. $11.10 for 10 pieces from JLCPCB) as an add-on to an existing PCB order


This PCB has an oval through hole into which you can solder the USB connector of a Raspberry Pi Pico (with piggyback Traquito). Using a tiny scrap wire segment, make the positive power connection to the Traquito. Use two PCBs for flight. The top PCB gets three SMD Schottky diodes installed (to "steer" or isolate the dark solar panels from the illuminated one). Use one more PCB (without diodes attached) as a bottom spreader or stiffener.

On the PowerFilm solar cells, you DO NOT need to remove the plastic covering ... just go ahead and solder them as shown! I have included STL files to 3D print a (optional) assembly jig to keep everything neat and square (and frustration free). 

Be sure to observe the +/- orientation when soldering the top and bottom PCBs to the solar cells!
