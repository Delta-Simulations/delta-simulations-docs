# Aircraft Selection and Tablet Troubleshooting

Start with the symptom you can reproduce. An aircraft missing from the selector, a missing tablet, and a disabled hoist button each point to a different part of the add-on.

| Symptom | First check | What to try next |
| --- | --- | --- |
| The H-60 is absent from the selector | Open the active Community folder from the simulator. Check for **deltasimulations-uh60 → manifest.json**. | Correct any extra folder level, restart MSFS, and search for **UH-60**. In MSFS 2024, also check **My Library → Community** and whether the package is enabled. |
| The aircraft loads but the tablet is missing | Look for the **PEDAL ADJUST** click spot. | Click once to restore the tablet. If the screen is present but dim, open **Settings → EFB BRIGHTNESS**. |
| Map is blank while the other tablet tabs work | The **Map** tab loads OpenTopoMap over the internet. | Check the provider's availability. The aircraft and settings pages use different data. |
| A tablet or cockpit control will not respond to a mouse click | Check the simulator's cockpit interaction mode. Delta designs the controls for **Legacy** interaction. | Try the same control on a stock aircraft variation using the Legacy setting where the simulator offers it. |
| **HOIST**, **PROBE**, or **BAMBI BUCKET** is grey | Check the full variation name in the selector. | An HH-60M Medevac has a hoist. A civilian Helitak already has a fixed tank, so the separate bucket selector is disabled. |
| A new livery shows the wrong equipment or cabin | Load the corresponding included livery and compare the tablet controls. | If the stock variant is correct, check which base model and H-60 release the repaint was made for. |

## Reproduce a package problem

Keep the downloaded ZIP, close the simulator, and move the previous H-60 package and third-party H-60 repaints to a backup folder outside Community. Install one fresh copy of the released aircraft and reproduce the issue with a stock variation. Restore the repaints one at a time if that resolves it.

For an issue report, include the H-60 release tag, MSFS edition and build, full aircraft variation, and the steps from loading the flight to seeing the problem. A cockpit screenshot showing the active tablet tab and an exterior screenshot of the selected model make a configuration problem much easier to identify. Use the project's [issue tracker](https://github.com/Delta-Simulations/MSFS-H-60M/issues) or its [support Discord](https://discord.gg/4pjxYUw8j7).
