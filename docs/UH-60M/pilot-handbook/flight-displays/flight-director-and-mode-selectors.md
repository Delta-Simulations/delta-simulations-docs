# Flight Director and Mode Selectors

On the primary flight display, **FD1** appears when MSFS reports the flight director active. The horizontal command bar shows the difference between commanded and current pitch. The vertical bar shows the difference between commanded and current bank. The bars can move while the aircraft remains under manual control.

## What the controls do in V5.2.4

| Cockpit control | Implemented response |
| --- | --- |
| **Flight director** | Toggles the simulator flight director. Look for **FD1** and the command bars on the PFD. |
| **HDG**, **ALT** | Send the simulator heading-hold or altitude-hold event. Their button-lamp definitions do not supply engagement feedback in this release. |
| **RADALT** mode | Sends the simulator's radio-altitude-mode event. The **RA** height readout has its own display logic. |
| **COUPLE**, **HOVER** | Toggle a local cockpit state and its lamp. The button action itself does not command autopilot master engagement or position hold. |
| **SPD**, **VS**, altitude preselect mode, roll navigation, vertical navigation, go-around | These button faces have no click command assigned in the V5.2.4 cockpit template. |

## Reading the cues

With a powered PFD in front of you, select the flight director and watch for **FD1**. The horizon still shows actual pitch and bank. The bars show what the simulator director commands. If the bars move after a change in reference, check actual heading or altitude separately before concluding the helicopter has followed them.

**REF-BARO**, **REF-HI**, **REF-LO** and **REF-TIME** identify the selected reference on the PFD. With **BARO** selected, the adjust control changes the pressure setting. **HI** and **LO** adjust the radar-altitude references. A change in the reference label does not engage an altitude hold. To compare two height readings on the same flight, see [barometric and radar altitude](barometric-and-radar-altitude.md).

If an aircraft drifts with the **HOVER** lamp on, keep flying the helicopter with the cyclic, collective and pedals. For unwanted control inputs, check [rotor trim and flight assistance](../controls-and-lighting/rotor-trim-and-flight-assistance.md) and the active hardware profile.

[Mode selector bindings](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/PackageSources/ModelBehaviorDefs/DeltaSim-UH60/DeltaSim_MFD_Template.xml) · [PFD command bars](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/src/instruments/src/PFD/Components/PFD/flightDirector.tsx) · [FD and reference indications](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/src/instruments/src/PFD/Components/PFD/ApReadout.tsx)
