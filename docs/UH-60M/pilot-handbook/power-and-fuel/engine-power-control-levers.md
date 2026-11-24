# Engine Power Control Levers

Each engine has a power control lever (PCL) overhead. In the virtual cockpit, the lever handle and the cutoff catch are two different mouse targets. This is usually the reason a lever seems stuck at the bottom of its travel.

## Moving a lever with the mouse

1. In a parked aircraft, move the cursor over the cutoff catch for the engine you want. Look for the **PCL CUTOFF** tooltip.
2. Click the catch to move the lever out of cutoff and into the bottom of its working range.
3. Move the cursor onto the lever handle. Click and drag the handle along its working range. The drag interaction uses sideways mouse movement.
4. To select cutoff again during shutdown, drag the handle back to the bottom of its range, then click the catch. The catch only changes position at the bottom.

Each lever moves independently. If engine 2's lever stays put while engine 1's moves, select the catch and handle on the engine 2 side. The fuel selectors beside the levers use a different interaction and show **ENG1 FUEL** or **ENG2 FUEL** in their tooltips.

## Reading the engine side correctly

The ignition key controls master ignition. The two starter buttons control individual starters. EICAS can show **ENG 1 STARTER ON** or **ENG 2 STARTER ON** according to the starter active in MSFS. A starter indication tells you which starter is engaged. It does not by itself confirm combustion or that a generator is supplying the aircraft.

Both sets of EICAS engine tapes take several readings from engine 1, including torque, gas-generator speed and oil pressure. Identical tape readings therefore cannot establish that both engines are running. The starter and engine oil messages have separate inputs for each engine. If you're reporting an issue on one side, include the lever position and the numbered messages along with a screenshot of the tapes.

The [Starting Engines checklist](https://docs.deltasimulations.ca/UH-60M/Procedures/Starting%20Engines/) gives the normal start and runup flow for the add-on.

[H-60 systems source](https://github.com/Delta-Simulations/MSFS-H-60M/tree/a403200d72edbfb01cfe243c0c05afc6e596882f/PackageSources/Simobjects/Airplanes/UH60)
