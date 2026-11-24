# Data Transfer and Aircraft Status

The bottom bezel labels the data page **JMVF**. Its right-hand softkey reads **LOAD DTS**. The on-screen status changes from **DTS – NOT LOADED** to **DTS – LOADED** when the instrument handles the load request.

## Waypoints and the moving map

The data page clears its existing markers, then reads the package's waypoint file. Each data row supplies a name, latitude and longitude. A fourth field can identify the marker type. Empty rows and rows without usable coordinates are skipped. Repeating the load replaces the marker set for that operation.

To distinguish a route issue from a marker issue, first check the **ND** for the departure and destination selected in MSFS. Then select **JMVF**, use **LOAD DTS**, and inspect the map at a scale and location where the expected marker would be visible. The status flag is set when the load is requested. It can say **LOADED** even when a row was skipped or a file failed to load. The status alone cannot confirm an individual waypoint or change your MSFS flight plan.

## IVHMS administration screen

Select **EICAS**, then press **EICAS** a second time to reach **IVHMS**. The **MAIN-ADMIN** screen shows the selected model, tail-number information, an aircraft version field and DTS status. The tail-number line draws from the simulator's aircraft ID and flight number. Compare those fields with your aircraft customization if the line looks unexpected.

The administration display includes an **ADMIN LOGIN** label. Its published screen implements configuration and status readouts. It provides no maintenance history or component-by-component diagnostic report. For active cockpit messages, return to **EICAS** and read the [crew alert guide](crew-alerts-and-test-indications.md).

[Data page and waypoint loading](https://github.com/Delta-Simulations/MSFS-H-60M/blob/a403200d72edbfb01cfe243c0c05afc6e596882f/src/instruments/src/PFD/Components/JMVF/JMVFBase.tsx) · [IVHMS fields](https://github.com/Delta-Simulations/MSFS-H-60M/blob/a403200d72edbfb01cfe243c0c05afc6e596882f/src/instruments/src/PFD/Components/IVHMS/IVHMSBase.tsx)
