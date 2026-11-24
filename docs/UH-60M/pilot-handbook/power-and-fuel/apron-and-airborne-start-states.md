# Apron and Airborne Start States

Where you begin a flight changes the systems you inherit. The H-60 package defines an apron preset for a parked start and a cruise preset for an airborne start. Use the same start type when comparing two installations or trying to reproduce a cockpit issue.

| What to look at | Apron preset | Cruise preset |
| --- | --- | --- |
| Main batteries | Both overhead battery switches off. | Both on, with the standby instrument battery armed. |
| Engines | Both at zero RPM with the starter switches off. | Running, with both power control levers at the top of their travel and both engine generator switches on. |
| Navigation sensors | EGI 1 and EGI 2 off. | EGI 1 and EGI 2 on. |
| Flight controls | Both SAS channels, FPS and trim off. | Flight initialization selects both SAS channels, FPS and trim. |
| Brakes and displays | Parking brake set. The helicopter can start with dark screens. | Display power buttons selected on. |

## A dark panel on the ramp

First look at the battery switches and the engine indications. If you selected a parking position, a quiet aircraft with its batteries off matches the apron preset. Follow [Before Start](https://docs.deltasimulations.ca/UH-60M/Procedures/Before_Start/) and [Cockpit Equipment Checks](https://docs.deltasimulations.ca/UH-60M/Procedures/Cockpit%20Equipment%20Checks/) from there. An airborne start has already selected several of those switches. Repeating every toggle from memory can turn a system back off.

## Comparing two sessions

For a repeatable comparison, use the same aircraft variant, airport, starting position and fuel load. Before touching a switch, capture the overhead panel and the MFDs. For an electrical issue, include the battery and generator positions. For an engine issue, include both power control levers and the numbered EICAS messages. Record whether the session began parked, in the air or from a saved flight. Those details help distinguish a difference in starting state from a switch that fails to respond.

[V5.2.4 aircraft systems](https://github.com/Delta-Simulations/MSFS-H-60M/tree/V5.2.4/PackageSources/Simobjects/Airplanes/UH60)
