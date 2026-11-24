# Navigation Display and Flight Plan

Select **ND** on the bottom bezel. The helicopter symbol sits in the circular map area. The boxed number at the top gives current gyro heading in degrees. The short marks around the compass are five degrees apart, with a longer mark every ten degrees.

## Reading the route

The ND reads waypoint positions and identifiers from the MSFS flight plan. With at least two waypoints, a magenta line joins them in flight-plan order. To see the route on a first flight, set a departure and destination in the simulator before entering the cockpit. Pick two familiar airports close enough to fit on the same map scale.

The box at the top always refers to helicopter heading. A route leg can run across the screen at a different angle, particularly before you turn to join it. In heading-up orientation, the aircraft symbol points up while the route rotates as you turn. In north-up orientation, the route holds its orientation and the aircraft symbol turns instead.

## When the map looks empty

- **Heading and aircraft symbol visible, no terrain picture.** The ND draws its compass and route on a plain background. A chart image is not part of this display format.
- **One waypoint visible, no magenta line.** The display needs two waypoint positions to draw the first leg.
- **Route missing after editing the flight plan.** Check the departure and destination in MSFS. The display reads the plan when its instrument loads. If you're trying to isolate a route issue, start a new flight with the plan already selected.

The RA readout at the right follows the same height ranges as the one on the primary flight display.

[Display source](https://github.com/Delta-Simulations/MSFS-H-60M/blob/a403200d72edbfb01cfe243c0c05afc6e596882f/src/instruments/src/PFD/Components/ND/NDBase.tsx)
