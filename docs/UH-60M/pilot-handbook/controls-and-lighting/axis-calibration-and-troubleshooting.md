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

## A bench check for a short-throw stick

Rest the stick at centre, move it a quarter of the way to the left, then hold it there. Repeat to the right and do the same on the pitch axis. Look at the response at rest, through the first part of the movement and at the held position. These observations answer three different questions.

| Observation | What it suggests | Next adjustment |
| --- | --- | --- |
| The input wanders while the stick is untouched but holds steady once displaced | Noise around centre | Increase the centre dead zone just enough to absorb the wandering input. |
| The centre is steady, but a small movement commands a large response on either side | More response near centre than you want | Soften the response around centre and repeat the quarter-travel check at both ends. |
| The input turns before the stick does or jumps back when you hold the stick still | Another axis, a repeated command, or a noisy device may be contributing | Inspect all connected devices and any external control mapping before editing the curve. |
| Both directions move together smoothly, but one endpoint is never reached | Limited physical travel or device calibration | Compare the two endpoints in the device's own input display. Recalibrate there if it also misses the endpoint. |

A long cyclic extension increases hand travel for the same movement at the base. If you change from a short grip to an extended one, first try the existing response through a few small hand movements. A curve that suited the short stick can give a noticeably slower response after fitting the extension.

## Collective and pedal checks

Set the collective lever to each end, then stop halfway. Watch the in-sim lever or the axis indicator at all three positions. If the ends are correct but the middle is difficult to set, look for a hardware detent or a centre dead zone carried over from an airplane profile. Move away from that detent and back to the same spot to see whether it repeats.

For pedals, rest both feet lightly at centre and move each pedal through the same distance in turn. If yaw also moves when you use a toe brake, search for that particular toe input. Changing yaw sensitivity cannot remove an unwanted second binding. A centred stick and level helicopter need not give the same result in flight. The parked input check isolates the hardware from wind, trim and piloting assistance.

[MSFS 2024 controller settings](https://flightsimulator.zendesk.com/hc/en-us/articles/16459737949980-Controller-Settings-FAQ)
