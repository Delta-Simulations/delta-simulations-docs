# Fuel Load and Cruise Endurance

Delta's V5.2.4 UH-60M flight model defines **two 180 US gal main tanks**. With both at the same percentage, 100% is 360 US gal total, 50% is 180 US gal total and 25% is 90 US gal total. Read both tank quantities when one has been edited independently. A half-full left tank and an empty right tank hold only 90 US gal between them.

Use the same units for fuel on board and fuel burn. If the fuel quantity is in pounds, use pounds per hour. If you take the quantity in gallons, measure gallons per hour. When a display gives a separate flow for each engine, add both flows before calculating endurance.

## Measure cruise burn in your copy of the sim

1. Choose a repeatable cruise condition. Record variant, gross weight, altitude and airspeed so you can use the result on a similar flight.
2. Once established in cruise, write down total fuel and simulation time. Repeat the reading after ten or more simulated minutes. Start and end the sample in level flight.
3. Subtract the second reading from the first. Multiply by 60, then divide by the elapsed minutes. A ten-minute sample uses a multiplier of six.
4. Keep a separate allowance for start, hover, climb and the ground time you expect on this flight. If the quantity never changes, check unlimited-fuel assistance or whether fuel was added during the sample.

## Example fuel log

These are sample readings for the arithmetic. Use your own measured burn for a flight plan.

| Item | Example |
| --- | ---: |
| Total fuel at the start of a 12-minute cruise sample | 1,320 lb |
| Total fuel at the end | 1,200 lb |
| Measured burn | (1,320 − 1,200) × 60 ÷ 12 = **600 lb/h** |
| Fuel remaining at the end of the sample | 1,200 lb |
| Fuel set aside by the simmer for arrival and reserve | 300 lb |
| Fuel available for the remaining cruise | 900 lb |
| Remaining cruise time at the sample rate | 900 ÷ 600 = **1 h 30 min** |

At a groundspeed of **90 kt**, 1.5 hours gives **135 NM** in those steady conditions. At **75 kt** the same fuel gives about **113 NM**. A headwind may leave endurance almost unchanged at a given power setting while shortening the distance you can cover. Update the estimate when the groundspeed, load or fuel flow changes.

[H-60 flight model](https://github.com/Delta-Simulations/MSFS-H-60M/blob/a403200d72edbfb01cfe243c0c05afc6e596882f/PackageSources/Simobjects/Airplanes/UH60/flight_model.cfg) · [Flight model reference fields](https://docs.flightsimulator.com/html/Content_Configuration/SimObjects/Aircraft_SimO/flight_model_cfg.htm)
