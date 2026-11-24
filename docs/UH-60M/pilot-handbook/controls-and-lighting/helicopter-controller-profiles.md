# Helicopter Controller Profiles

In MSFS 2024, select the H-60 at the top of **Settings → Controls**, then select your stick, throttle quadrant or pedals from the device list. Each device has its own assignments. If you select the stick while trying to bind the pedals, the pedals won't appear in the assignment you're editing.

## Four axes for the H-60

| Physical movement | Search term | Assignment |
| --- | --- | --- |
| Stick forward and back | Cyclic longitudinal | Pitch axis |
| Stick left and right | Cyclic lateral | Roll axis |
| Pedals, or the twist grip on a stick | Tail rotor | Yaw axis |
| Collective lever, or one lever on a throttle quadrant | Collective | Collective axis |

Choose the continuous **axis** command for each lever or stick movement. Commands such as *increase*, *decrease*, *left* and *right* apply a step each time you press a button. An analog axis sends its position throughout the travel. A throttle quadrant works as a collective once you assign its lever to collective. The separate helicopter throttle command operates a different control.

## Where to save a binding

Use the helicopter category profile for the axes you want to carry between helicopters. Use the H-60 model profile for its special controls, such as the searchlight. For example, its searchlight uses commands labeled as cowl flaps in the simulator. Keeping those assignments in the H-60 profile leaves the same buttons available for other aircraft.

To keep a working preset, use the gear next to its name to duplicate it. A name like *H-60 – twist grip* or *H-60 – pedals* makes it easier to switch between the two setups. If you have both a twist stick and pedals, give yaw to the device you plan to use on this flight.

## Finding a command

Set the filter to **None** when looking for an unassigned command. **Assigned** is useful once you want to review the bindings already on that device. To see what a specific physical input does, choose **Search by input** and move just that axis or press just that button. If a number appears beside a binding, open its gear to see the conflicting assignments.

## Example layouts

**Spring stick and single throttle.** Use the two stick axes for cyclic, the twist for tail rotor and the throttle lever for collective. Reserve one thumb button for rotor trim reset. A hat can take the four directional rotor trim commands if you use them frequently. Check the hat in **Search by input** before assigning all four directions. Many stock stick profiles already use it for quick views.

**Cyclic, collective and pedals.** Assign both cyclic axes on the cyclic device, collective on the lever device, and tail rotor on the pedal device. Toe brakes are two extra axes on many pedal sets. Push the left pedal forwards with your heel down, then press just its toe brake. Verify they register as different inputs before assigning yaw. A spare twist on the cyclic can stay unassigned.

**Two levers on one quadrant.** Decide which lever will represent collective. Leave the other clear while checking movement. Linking the handles mechanically while one still sends an engine throttle command can make the engine and collective controls move together. If the throttle levers and collective both move, search for the physical lever on the quadrant and check its assignments in each active profile.

## Hardware software and event IDs

Some bindings programs use an event name instead of the action shown in the MSFS menus. These are the four continuous inputs in the MSFS SDK.

| Axis | Simulator event |
| --- | --- |
| Cyclic, left and right | `AXIS_CYCLIC_LATERAL_SET` |
| Cyclic, fore and aft | `AXIS_CYCLIC_LONGITUDINAL_SET` |
| Collective | `AXIS_COLLECTIVE_SET` |
| Tail rotor | `AXIS_TAIL_ROTOR_SET` |

If the hardware sends events through another application, switch off its aircraft profile briefly when tracing duplicate inputs. **Search by input** finds assignments made inside MSFS for the selected device. Commands sent separately by a hardware application can still reach the aircraft even when the MSFS search comes up empty.

[MSFS 2024 controller settings](https://flightsimulator.zendesk.com/hc/en-us/articles/16459737949980-Controller-Settings-FAQ) · [Helicopter axis commands](https://docs.flightsimulator.com/msfs2024/retail/programming-apis/key-events/helicopter-specific-events/)
