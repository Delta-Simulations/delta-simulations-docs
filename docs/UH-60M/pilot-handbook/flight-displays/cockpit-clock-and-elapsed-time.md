# Cockpit Clock and Elapsed Time

The cockpit clock has a sweep seconds hand and two rows of digits. The top row shows hours and minutes on a 24-hour clock. The second row shows seconds. For example, **1437** above **08** reads 14:37:08. The letter at the bottom tells you which time you're looking at.

| Mode | What the digits show |
| --- | --- |
| **C** | Local time in the simulator. When recording a VATSIM time in UTC, account for the difference between local time and UTC. |
| **ET** | Elapsed hours, minutes and seconds. Use it to time a route leg or a hover exercise. |

## Timing a leg

Use **Clock Mode toggle** to select **ET**. **Clock Control** cycles through run, stop and reset. With the timer reset at zero, press **Clock Control** as you pass the first waypoint. Press it again at the next waypoint to hold the reading. Read the result before pressing the control a third time to reset it.

If the time looks frozen, check the letter at the bottom. **ET** can hold a stopped time, while **C** follows the simulator clock. Switching between C and ET changes which time you see. A reset is a separate action on **Clock Control**.

[V5.2.4 instrument reference](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/src/instruments/src/AP/Components/Clock/Clock.tsx)
