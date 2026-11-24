# Navigation Receivers and Transponder

The aircraft configuration supplies two NAV receivers, an ADF receiver, a marker beacon receiver and one transponder. The moving map gets its route from the simulator flight plan. Changing a radio frequency leaves that route in place.

## NAV1 and NAV2

Both NAV receivers have standby tuning. NAV1 is configured for a glideslope signal. NAV2 is configured without glideslope. For an offline receiver check, choose a station from the simulator's navigation data, tune the standby frequency on the intended receiver and transfer it to active. If you use a hardware panel, verify both the NAV receiver number and the active window. COM tuning on the same hardware controls a different pair of radios.

Receiving a signal, displaying its guidance and coupling a flight control mode are three separate functions. The V5.2.4 ND draws a magenta line between flight-plan waypoints. That line can appear with either NAV receiver tuned elsewhere. The cockpit **vertical navigation** and **roll navigation** keys have no assigned click command in this build. A visible route line alone is insufficient evidence of approach capture. See [flight director and mode selectors](../flight-displays/flight-director-and-mode-selectors.md).

## Transponder on VATSIM

Use the four-digit code assigned to your flight. With vPilot you can enter `.x` followed by a space and the assigned code. Copy all four digits, including a leading zero. **Mode C** and **standby** are separate from the code. Use the transponder mode control in vPilot to check which state the client is reporting. When a controller asks for **IDENT**, use the client's Ident control. This briefly highlights the existing return and leaves the assigned code in place.

| Symptom | Where to look |
| --- | --- |
| The code is correct but the controller asks for altitude reporting | Check the client's Mode C/standby indication. Re-entering the same code only changes the code field. |
| A pedestal key moves but the client shows no change | Use the client's supported transponder command or control and read back the resulting indication. |
| The destination appears on the map after changing frequencies | Compare the destination identifier with the simulator flight plan. Receiver tuning and route editing are independent. |

[H-60 receiver configuration](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/PackageSources/Simobjects/Airplanes/UH60/systems.cfg) · [vPilot transponder controls](https://vpilot.rosscarlson.dev/Documentation)
