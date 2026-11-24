# Rotor Trim and Flight Assistance

The H-60 has buttons labeled **SAS 1**, **SAS 2**, **FPS** and **TRIM**. MSFS also has controller commands with the word *trim* in their names. Which one you select matters, especially on a spring-centred stick.

## Controls in the aircraft

**SAS** stands for stability augmentation system. **FPS** stands for flight path stabilization. The H-60's cockpit equipment checks group the two SAS channels with FPS and trim. In the model, each of the four buttons toggles its own state. Pressing the cockpit control labeled **TRIM RESET** does something different. It sends the simulator's rotor trim reset command.

If you're following a checklist item that calls for the AFCS trim switch, look for **AFCS TRIM**. If you're testing a controller profile and need to clear a rotor trim offset, use **TRIM RESET**. Selecting the four AFCS buttons alone doesn't establish an altitude, heading or hover hold.

## Commands for a spring-centred stick

| MSFS function | Effect |
| --- | --- |
| Longitudinal rotor trim | Adjusts pitch trim fore or aft. |
| Lateral rotor trim | Adjusts roll trim left or right. |
| Rotor trim reset | Restores the default rotor trim values. |
| Helicopter force trim release | Holds the simulated cyclic position while you recentre a physical stick. Releasing the button reconnects the stick at the new reference. |

For the MSFS **force trim release** function, use a momentary button you can hold and release. With the helicopter parked, move the stick off centre, hold the button, return the physical stick to centre, then release. This lets you check whether your control profile sends both the press and the release. A latching switch can leave the release command held. This is a simulator input function and does not require a force feedback base.

## Simulator assistance

MSFS 2024 lists **Assisted cyclic**, **Assisted tail rotor** and **Assisted collective** as separate piloting assists. When comparing how two profiles handle, use the same assistance settings for both flights. A pilot checking a new set of pedals, for example, can compare the same short flight with just the tail rotor assistance changed. That makes the effect easier to distinguish from a new yaw response curve.

[H-60 cockpit controls](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/PackageSources/Simobjects/Airplanes/UH60/Model/UH60Mint.xml) · [MSFS helicopter trim commands](https://docs.flightsimulator.com/msfs2024/retail/programming-apis/key-events/helicopter-specific-events/) · [MSFS piloting assists](https://www.flightsimulator.com/accessibility-msfs-2024/)
