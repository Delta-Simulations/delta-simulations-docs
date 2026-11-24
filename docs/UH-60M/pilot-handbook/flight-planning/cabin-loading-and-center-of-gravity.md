# Cabin Loading and Center of Gravity

Gross weight tells you how much the rotor must support. Center of gravity (CG) tells you where that weight acts. Move a load between two stations and the total stays the same, while the balance changes. This is useful when two saved flights show the same weight but need different amounts of cyclic to hold the same attitude.

## Station positions

These offsets are from the stock UH-60M flight model in V5.2.4. **Forward** and **right** are positive in the simulator's coordinate system. The datum is an imaginary reference point set by the model developer. These figures apply to the simulator's loading stations.

| Station | Fore/aft arm | Left/right arm |
| --- | ---: | ---: |
| Pilot | +6.5 ft | −2.3 ft |
| Copilot | +6.5 ft | +2.3 ft |
| Gunner Left | +1.6 ft | −2.0 ft |
| Gunner Right | +1.7 ft | +2.0 ft |
| CARGO | −6.0 ft | 0 ft |

Adding weight to **CARGO** moves the CG toward that aft station. Splitting an equal load between the two forward seats cancels their left/right moments because their lateral arms are equal and opposite.

## Same weight, different balance

Try two loadouts at the same fuel quantity. In the first, leave the copilot seat empty and put at least 150 lb in **CARGO**. In the second, subtract 150 lb from **CARGO** and enter 150 lb at the copilot station. The weight has moved **12.5 ft forward** and **2.3 ft right** in the model.

For an aircraft weighing exactly 15,000 lb in this example:

| Change | Calculation | CG shift |
| --- | --- | ---: |
| Fore/aft | 150 lb × 12.5 ft ÷ 15,000 lb | 0.125 ft, or **1.5 in forward** |
| Left/right | 150 lb × 2.3 ft ÷ 15,000 lb | 0.023 ft, or **0.28 in right** |

The movement can be too small to see on a coarse CG graphic. Check the station totals and the direction of the change before judging it by helicopter attitude. Compare loadouts with the same wind, fuel and controller trim. A steady wind or an off-center input can otherwise feel like a loading difference.

[H-60 flight model](https://github.com/Delta-Simulations/MSFS-H-60M/blob/a403200d72edbfb01cfe243c0c05afc6e596882f/PackageSources/Simobjects/Airplanes/UH60/flight_model.cfg) · [Flight model reference fields](https://docs.flightsimulator.com/html/Content_Configuration/SimObjects/Aircraft_SimO/flight_model_cfg.htm)
