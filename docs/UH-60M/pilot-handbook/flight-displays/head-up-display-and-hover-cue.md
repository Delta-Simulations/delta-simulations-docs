# Head-Up Display and Hover Cue

The collective has a **HUD Toggle** control. From the pilot's view, the head-up display puts airspeed, groundspeed, a drift cue and a height scale in the forward field of view. Set the seat position first so you can see both sides of the display. Keep the PFD available as a second reference.

| HUD indication | How to read it |
| --- | --- |
| Number followed by **A** | Indicated airspeed in knots, rounded down to a whole knot. |
| Number followed by **G** | Groundspeed in knots, also rounded down. It can differ from airspeed on a windy day. |
| Line with a small square | The square moves with forward and sideways velocity in aircraft axes. Its displacement shows drift relative to the nose. |
| Right-hand bar | Height over the surface. In V5.2.4 the bar reaches full travel at 250 ft. |
| Right-hand pointer | Vertical speed. It can move while the height bar is already at full travel. |

## Reading drift near the ground

For an offline check, use a flat apron with a painted marking and calm preset weather. Note where the square sits while parked. In a steady low hover, compare the square with movement of the marking below. Sideways displacement of the square corresponds to sideways travel relative to the aircraft. The symbol measures motion and supplies no automatic position hold.

In wind, **A** and **G** can differ even with the nose held steady. When judging movement over a landing spot, use the ground reference and **G**. When comparing airspeed with the PFD, use **A**. At very low speed the PFD's digital airspeed window has a display floor, so the two digital numbers can disagree on the ramp.

The HUD height bar and the [PFD radar-altitude display](barometric-and-radar-altitude.md) have different ranges. As a simulator example, the HUD bar can remain full while climbing from 300 to 400 ft above a flat field. The PFD can still show the change in height. The altitude dial on the PFD uses the barometric setting and answers a different question again.

[HUD speed readouts](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/src/instruments/src/HUD/Components/Fixed_Readout.tsx) · [Drift cue](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/src/instruments/src/HUD/Components/HoverIndicator.tsx) · [HUD height scale](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/src/instruments/src/HUD/Components/RAIndicator.tsx)
