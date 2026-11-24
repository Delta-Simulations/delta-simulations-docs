# Axis Calibration and Troubleshooting

With the H-60 parked, check each physical axis before adjusting how the helicopter handles. Open **Controls**, select the device, then open **Hardware settings** for that axis. Watch its input indicator as you move the control. Make a copy of your usual profile first if you're experimenting with response curves.

## Centre, direction and travel

1. **Check the centre.** Rest a spring-centred stick or the pedals and take your hands or feet off. If the indicator jitters, add a small centre dead zone and observe the same input again. Stop increasing the dead zone once the jitter disappears. A collective or throttle lever can rest anywhere in its travel and has no equivalent spring centre.
2. **Check each direction.** Move fore and aft with the stick held close to centre on the other axis. Then repeat left and right. If the wrong axis responds, correct the assignment. If the correct axis responds backwards in the cockpit, reverse that axis.
3. **Check the ends.** Move through the full stroke slowly. The indicator should change smoothly. A gap in the middle and a shortfall at the end are different problems. Compare the reading with the device's own calibration screen before changing the response curve.
4. **Check with all your devices connected.** Move one control while leaving the others still. If the input jumps back to another position, inspect the bindings on the second device as well. This is easy to miss with a gamepad left connected beside a HOTAS.

## Common symptoms

| What you see | What to check |
| --- | --- |
| Twisting the stick changes the nose direction even though pedals are connected | Look for a yaw or tail rotor binding on both devices. Clear the one you aren't using in the active profile. |
| Moving the quadrant changes a throttle lever while the collective stays put | Search by that physical input and check whether it is assigned to helicopter throttle, collective, or both. |
| The cyclic barely responds around centre, then moves suddenly | Compare the physical input indicator with the response curve. A large dead zone uses up part of the available travel. |
| A button changes the control a little at a time | Check whether an increment or decrement command was chosen in place of an axis. |
| A change worked yesterday but has disappeared | Select the H-60 and check the active profile on the actual device. The stick and quadrant can each have a different profile selected. |

For small adjustments, change one setting and repeat the same movement. Start with direction and range, then adjust sensitivity until small movements feel manageable with your stick length and grip.

[MSFS 2024 controller settings](https://flightsimulator.zendesk.com/hc/en-us/articles/16459737949980-Controller-Settings-FAQ)
