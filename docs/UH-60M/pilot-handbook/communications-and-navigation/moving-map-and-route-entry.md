# Moving Map and Route Entry

To put a route on the **ND**, set the departure, destination and any intermediate waypoints in the simulator flight planner before loading the flight. Select **ND** and look for the line between the first two waypoints. The pedestal **DIR** key has no assigned click action in V5.2.4. Pressing it will not create a direct-to leg on the map.

## Three ways to look at the route

| Display | What it shows | When to use it |
| --- | --- | --- |
| **ND** | Heading, waypoint identifiers and lines joining the simulator flight-plan positions. | Trace the order of the legs or find the next turn. |
| **TAC** | A moving map with orientation, scale, centering and symbol controls. | Match the helicopter's position to nearby map features. |
| Cockpit tablet **Map** | A separate map on the aircraft tablet. | Keep a map open while the two front displays show flight and engine instruments. |

On the moving map, **ORIENT** shows **NORTH** or **HDG**. In north-up the map holds its orientation while the aircraft symbol rotates. In heading-up the aircraft stays pointed up and the map rotates underneath it. If the line to the destination appears sideways after changing orientation, compare the waypoint names first. The change affects the picture, not the leg sequence.

**MAP CTR** selects a centered or offset presentation. The offset gives more room in front of the aircraft. **ZOOM** changes the area you see, and **DECL** changes how much symbology is drawn. When an expected feature goes missing, restore a wider scale and check declutter before editing the route.

## Check an empty map

Start a short flight between two airports you know. First find the two airport identifiers on the ND. If only one waypoint is available, there is no leg to join. Switch to the moving map and locate the aircraft on the ramp. Change one setting at a time so you can distinguish a change in scale from a change in orientation. Extra markers loaded through **JMVF** are separate from the route. See [data transfer and aircraft status](../flight-displays/data-transfer-and-aircraft-status.md).

[Moving map display](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/src/instruments/src/PFD/Components/TacMap/TacMap.tsx) · [Map labels](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/src/instruments/src/PFD/Components/TacMap/TacMapSideBar.tsx) · [Pedestal key bindings](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/PackageSources/ModelBehaviorDefs/DeltaSim-UH60/DeltaSim_MFD_Template.xml)
