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

[H-60 searchlight bindings](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/PackageSources/Simobjects/Airplanes/UH60/Model/UH60M.xml) · [H-60 light controls](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/PackageSources/Simobjects/Airplanes/UH60/Model/UH60Mint.xml) · [H-60 lighting logic](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/PackageSources/Simobjects/Airplanes/UH60/Panel/Systems/Systems.xml)
