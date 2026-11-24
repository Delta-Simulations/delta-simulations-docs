# Exterior Lights and Searchlight

The H-60 has position lights, upper and lower anti-collision beacons, a landing light and a steerable searchlight. For a quick visual check, park near a patch of unlit pavement and use the external camera. It is easier to distinguish the two forward lamps when you can see both the fixture and where its beam lands.

## Position lights and beacons

The position lights are red on the left, green on the right and white at the tail. Their selector is labeled **NAV DIM**, **NAV OFF** and **NAV BRT**. For the anti-collision lights, one switch selects **UPPER**, **BOTH** or **LOWER**. The other selects **DAY**, **OFF** or **NIGHT**. If one beacon is missing, check the first switch. If neither beacon is visible, check the second switch. The add-on uses different effects for the day and night settings.

## Landing light and searchlight

The cockpit has two individual push controls. **Search Light CNTRL** switches the steerable lamp. **Landing Light CNTRL** switches the landing lamp. When using generic lighting commands from a hardware panel, the searchlight uses the simulator's *landing light* channel and the landing lamp uses the *taxi light* channel. If your hardware switch operates the other lamp, try the labeled cockpit control to identify it first.

Four button assignments position the searchlight. The aircraft intercepts the following MSFS cowl flap commands, which explains their unusual names in a hardware profile.

| Searchlight motion | MSFS event |
| --- | --- |
| Extend | `INC_COWL_FLAPS4` |
| Retract | `DEC_COWL_FLAPS4` |
| Left | `INC_COWL_FLAPS3` |
| Right | `DEC_COWL_FLAPS3` |

The directional inputs move the fixture in small steps. With power available, extend the light several steps before checking left and right travel. At full retraction, the model returns the sideways aim to centre. If the lamp is lit but appears to ignore sideways commands, check that it has moved out of the stowed position. To confirm that a four-way hat is wired as intended, leave the helicopter stationary and move the beam across the same patch of pavement.

## Building a four-way searchlight hat

Use **out** and **in** on the fore-and-aft hat directions and **left** and **right** on the side directions. Start with only **out** assigned. With the helicopter parked and powered, switch on the searchlight and tap the assigned direction several times. Check for fixture movement in the external view, then watch the pool of light on the pavement. Once you can identify that motion, add the other three directions. Separate the command that switches the lamp on from the four commands that move it.

The model steps extension from retracted to fully extended and back. The left/right mechanism also has end stops. One press near an end stop may be difficult to see. Move it back towards the middle before deciding that the other binding is faulty. The model resets horizontal aim to mid-travel at full retraction. To repeat a sweep from the same starting point, retract, extend, then try the lateral input.

## Exterior light checks

| Symptom | Observation | What to try in the sim |
| --- | --- | --- |
| A light comes on but the four-way hat seems ineffective | The stationary landing beam is visible while the searchlight is dark | Switch off the landing lamp briefly and identify the searchlight beam on its own. |
| The searchlight extends but never moves farther left | The lamp may already be at the left stop | Tap right several times and then left. If neither works, recheck the two engine 3 cowl flap assignments. |
| The pilot's view also moves | The same hat direction is assigned to camera look | Use **Search by input** on that direction. Move the conflicting camera assignment to a different control. |
| A beacon changes from one fitting to two but still looks dark | Lamp selection and power mode are independent | Check the **DAY/OFF/NIGHT** selector as well as **UPPER/BOTH/LOWER**. |
| Formation lights change but the red and green positions do not | Formation lighting has its own rotary control | Return to the nav selector for position lights. Its middle position is off. |

The v5.2.4 nav switch tooltips and the configured intensity values disagree at the two on positions. The tooltip labeled **NAV DIM** selects the higher output in the systems logic and **NAV BRT** selects the lower output. Compare both in the same light from the same external view when matching the brightness for a screenshot. The centre position switches the nav lights off.

[H-60 searchlight bindings](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/PackageSources/Simobjects/Airplanes/UH60/Model/UH60M.xml) · [H-60 light controls](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/PackageSources/Simobjects/Airplanes/UH60/Model/UH60Mint.xml) · [H-60 lighting logic](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/PackageSources/Simobjects/Airplanes/UH60/Panel/Systems/Systems.xml)
