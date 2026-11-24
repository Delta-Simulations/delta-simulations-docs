# Barometric and Radar Altitude

The PFD has two altitude indications in feet. **FEET** is barometric altitude. **RA** is height over the terrain beneath the helicopter. Both can be correct while showing very different numbers.

## Barometric altitude

The large numbered dial uses the simulator's indicated altitude. Each full turn of the needle represents 1,000 feet. Read the digital window for the thousands as well as the hundreds. It moves in 10-foot steps. The pressure setting alongside the dial is marked **IN**, for inches of mercury.

For example, at an airport about 4,000 feet above sea level, the dial should read roughly 4,000 feet on the ground when the pressure setting matches the local altimeter setting. It will continue to read about 4,000 feet as you taxi across a level ramp.

## Radar altitude

At that same airport, **RA** should read near zero on the ground. In level flight, RA decreases as the ground rises beneath you even if barometric altitude holds steady. The navigation display also carries an RA readout, so you can check height above terrain while looking at the route.

| Height over terrain in V5.2.4 | RA indication |
| --- | --- |
| Up to about 1,050 feet | Dial and digital height. |
| Above about 1,050 through 1,500 feet | Digital height only. |
| Above about 1,500 feet | The RA dial and digital height drop out. Barometric altitude remains available on the PFD. |

If the RA number disappears during a climb, check the height range before changing display settings. When crossing sloping terrain, use the vertical speed indication to check whether the helicopter itself is climbing or descending.

[V5.2.4 instrument reference](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/src/instruments/src/PFD/Components/PFD/AltCircle.tsx)
