# Gross Weight and Payload Stations

The stock **UH-60M 20743** in Delta Simulations V5.2.4 starts from a configured empty weight of **12,511 lb**. Its flight model lists **23,000 lb** as the maximum gross weight. The difference, **10,489 lb**, has to cover everyone on board, cargo and fuel together. Use the loaded weight shown in MSFS for the aircraft in front of you. A saved flight can start with different quantities at every station.

## The five payload stations

Open the aircraft's fuel and payload settings and read the station weights before changing them. The table gives the defaults in the released flight model.

| Station in the model | Default load | Where the weight goes |
| --- | ---: | --- |
| Pilot | 200 lb | Forward seat, left side of the model datum |
| Copilot | 200 lb | Forward seat, right side of the model datum |
| Gunner Left | 200 lb | Left cabin crew position |
| Gunner Right | 200 lb | Right cabin crew position |
| CARGO | 1,000 lb | Aft of the cabin crew, on the centerline |

Together these defaults add **1,800 lb**. With the tanks empty, that gives **14,311 lb**. A station value is a total. To put 350 lb of baggage in a station that currently shows 1,000 lb, enter **350**, which removes 650 lb from the aircraft. When changing a visible crew or cabin option, check the station readouts separately.

## Example load for a short flight

For two occupants and baggage, enter 190 lb for the pilot, 170 lb for the copilot, zero for each cabin crew station and 350 lb for cargo. The five entries total **710 lb**. If the sim shows **1,200 lb of fuel**, the departure gross weight is:

**12,511 + 710 + 1,200 = 14,421 lb.**

If MSFS shows a different total, first check whether your fuel is displayed in gallons and whether a station still contains its default load. A common discrepancy in this example is exactly 400 lb from the two occupied cabin crew positions. Once the total agrees, check where the load sits. Two aircraft at the same gross weight can have different centers of gravity.

[H-60 flight model](https://github.com/Delta-Simulations/MSFS-H-60M/blob/a403200d72edbfb01cfe243c0c05afc6e596882f/PackageSources/Simobjects/Airplanes/UH60/flight_model.cfg) · [Flight model reference fields](https://docs.flightsimulator.com/html/Content_Configuration/SimObjects/Aircraft_SimO/flight_model_cfg.htm)
