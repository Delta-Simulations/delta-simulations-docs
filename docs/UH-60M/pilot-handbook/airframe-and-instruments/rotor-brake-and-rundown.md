# Rotor Brake and Rundown

The rotor brake acts on the revolving drive system. The parking brake acts at the wheels, and the tailwheel lock limits wheel swivel. Each has a separate cockpit control. On an exterior view the helicopter can sit perfectly still while the blades are still turning.

## Reading the shutdown indications

Keep EICAS in view for the engine and rotor portion of the [parking and shutdown checklist](../../Procedures/Parking%20and%20Shutdown.md). Watch the **NR** indication as the rotor slows. The checklist gives the sim's rotor-brake point as **at or below 40% NR**. Use the instrument for that reading. At some frame rates the exterior blade animation can look almost stationary while the rotor is still turning.

The cockpit rotor brake has two tooltip states, **ROTOR BRAKE (UNLOCKED)** and **ROTOR BRAKE (ENGAGED)**. Clicking the lever toggles the aircraft's local brake selection. While that selection is engaged, the model repeatedly sends the simulator's rotor-brake-on command. The lever animation reads the simulator's active brake state.

## A brake that appears to reapply itself

If an external controller releases the brake for an instant and the lever returns to engaged, click the cockpit lever to unlock it and check the tooltip again. A generic controller release can conflict with the cockpit's retained selection. On the next parked session, compare the same cockpit action with the controller disconnected or its rotor brake assignment temporarily cleared.

If the wheels roll with the rotor stopped, check the [parking brake and tailwheel lock](../flight-deck/parking-brake-and-tailwheel-lock.md). An unlocked tailwheel permits swivel while moving. It cannot hold a parked helicopter in place. When reporting an apparent brake fault, identify which object moved: blades, wheels, or the tailwheel pivot.

[Cockpit rotor-brake lever](https://github.com/Delta-Simulations/MSFS-H-60M/blob/a403200d72edbfb01cfe243c0c05afc6e596882f/PackageSources/Simobjects/Airplanes/UH60/Model/UH60Mint.xml) · [Engine and rotor indications](../flight-displays/engine-and-rotor-indications.md)
