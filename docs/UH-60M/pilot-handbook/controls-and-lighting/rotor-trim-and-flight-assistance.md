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

## Reading the panel

The four AFCS pushbuttons have separate annunciators. With the panel powered and the annunciator test off, click **SAS 1** once and watch the SAS 1 annunciator. A second click returns that channel to its previous selection. The other channel, **SAS 2**, has its own button and annunciator. **FPS** and **TRIM** work the same way as panel selections. If the start configuration has already selected them, clicking each one from memory will deselect it. Read the indication before changing it.

The rotor trim reset is a momentary command. It clears a trim offset without changing those four panel selections. This is useful on a desktop stick after a previous session left an unexpected pitch or roll bias. A trim reset can change the commanded cyclic offset immediately. Try it in a parked or otherwise controlled simulator setup when first identifying the binding.

## A spring-stick setup

Put fore/aft and left/right rotor trim changes on a four-way hat. Assign the simulator's **force trim release** to a grip button that reports both press and release. Leave **rotor trim reset** on a separate button. The three functions give a hat for small corrections, a held button for changing the stick's physical reference, and a way to recover the original trim. If your stick has only one hat, check whether the camera is still assigned to it.

| Symptom | What to look at | What to change |
| --- | --- | --- |
| The in-sim cyclic stops following the hand controller after a trim input | A maintained switch or button profile can keep force trim release active | Use a momentary press-and-release binding. Verify the stick tracks again after release. |
| Moving the trim hat pans the camera | Search by the physical hat direction on the stick | Assign the view elsewhere or use a separate profile for the hat. |
| Touching reset repeatedly changes the AFCS trim annunciator | The button is operating the cockpit AFCS trim toggle | Use the rotor trim reset command when the goal is to clear pitch and roll bias. |
| Two pilots get different behaviour with the same joystick preset | Compare cyclic, tail rotor and collective assistance settings separately | Repeat with the same assistance setup, weather and starting state before comparing curves. |

The simulator's force trim release changes the reference between joystick input and virtual cyclic. Motor forces and physical centring on a force feedback base also depend on the device and its driver profile. A correctly functioning virtual trim button alone does not establish the force settings for a particular base.

[H-60 cockpit controls](https://github.com/Delta-Simulations/MSFS-H-60M/blob/a403200d72edbfb01cfe243c0c05afc6e596882f/PackageSources/Simobjects/Airplanes/UH60/Model/UH60Mint.xml) · [MSFS helicopter trim commands](https://docs.flightsimulator.com/msfs2024/retail/programming-apis/key-events/helicopter-specific-events/) · [MSFS piloting assists](https://www.flightsimulator.com/accessibility-msfs-2024/)
