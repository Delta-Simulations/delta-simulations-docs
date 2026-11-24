# Cockpit and Cabin Lighting

The cockpit has separate controls for backlit lettering, floodlights and the utility light at each seat. The cabin has its own colour selector. In a night flight, decide what you need to see first. If the lettering on the overhead is hard to read, raise the overhead backlight. If you need to see the shape of a switch or an unlit surface, use a flood or utility light.

## Panel illumination

| Cockpit control or tooltip | Area to watch |
| --- | --- |
| **OH PNL BACKLIGHT** | Overhead panel lettering |
| **INST PNL BACKLIGHT** | Instrument panel backlight |
| **LWR CSL BACKLIGHT** | Lower console, radio panels and collective lettering |
| **LIGHTED SWITCH INTENSITY** | Illumination of the lighted switches |
| **PILOT MASTER WARNING LIGHTING** / **COPILOT MASTER WARNING LIGHTING** | Master warning lighting on the selected side |

The panel knobs above move in ten-percentage-point steps in version 5.2.4. One or two clicks at a time make it easier to balance adjacent panels. If the radios and collective labels are too bright while the overhead looks right, turn down **LWR CSL BACKLIGHT** and keep the overhead setting.

## Flood and utility lights

The cockpit floodlights cover a wider area. Their brightness knob has finer five-point steps. **COCKPIT LIGHT COLOUR** switches between the white and green floodlight effects. Colour and brightness are separate controls, so changing colour at zero brightness produces little to see.

Each seat also has **UTIL LIGHT MODE** and **UTIL LIGHT POWER**. Mode changes the colour of that seat's utility light. Power adjusts its intensity in twenty-point steps from off to full. If the other seat is lit and yours is dark, adjust the control for your side. This is a useful option when you want a little light at one seat without flooding the entire cockpit.

## Cabin lights

The cabin switch has three labeled positions, **WHITE**, **OFF** and **BLUE**. View the cabin behind the seats to see the change. The cockpit floodlight colour selector and utility light knobs affect the flight deck, so they can be left where you want them while changing the cabin lights for a passenger view or screenshot.

## Night lighting from the pilot seat

1. Select the **Overhead** instrument view. Turn the overhead panel dimmer clockwise and look for the lettering around the switches to brighten. Turn it back down a click at a time until the letters are readable. The lettering circuit responds to the in-sim master battery, so a fully bright dimmer on a dark, unpowered cockpit is a poor test.
2. Move to the **Pedestal** view and adjust the lower console backlight. The lower radio panels and the lettering on the collective share this setting. One is a good reference while setting up the other.
3. Return to the pilot view. Use the floodlight if you can read lettering but cannot distinguish the unlit surfaces around it. Turning the flood knob clockwise increases its intensity. Choose a colour with the flood colour switch.
4. Use the pilot utility light for a smaller illuminated area. Starting at zero, two clockwise steps give the utility lamp a 40 percent setting. The copilot lamp will retain its own setting. Finish by looking outside from the seat you'll actually use.

## When the lighting looks wrong

| What you see | Likely control or condition |
| --- | --- |
| Lower radio panel and collective lettering dim together | Both use the lower console setting. The overhead dimmer controls a different zone. |
| Switching floodlight colour seems to do nothing | Bring the secondary flood brightness above zero. Watch an unlit cockpit surface rather than a backlit label. |
| Pilot utility light changes while the copilot's light stays dark | Each seat has separate mode and power controls. Select the other seat's lamp. |
| Cabin switch says **BLUE**, but the rear cabin looks greenish | In v5.2.4 the switch tooltip reads **BLUE** while the selected lighting effect is green. Moving through **OFF** and back to **BLUE** makes the change easier to see. |
| Multiple annunciators light together | The **TEST ANNUN** control can illuminate the lamps for a test. End the test before reading individual AFCS or system selections. |

Version 5.2.4 sets some lighting selections according to the simulator time of day when the aircraft first loads. The cabin, cockpit flood and utility lamp modes can therefore start in different positions on a daytime and a nighttime spawn. Read the controls after loading if you are comparing screenshots between flights.

[Lighting and startup logic](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/PackageSources/Simobjects/Airplanes/UH60/Panel/Systems/Systems.xml) · [Panel illumination](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/PackageSources/ModelBehaviorDefs/DeltaSim-UH60/DeltaSim_Lighting_Template.xml) · [H-60 interior lighting controls](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/PackageSources/Simobjects/Airplanes/UH60/Model/UH60Mint.xml) · [H-60 lighting circuits and effects](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/PackageSources/Simobjects/Airplanes/UH60/systems.cfg)
