# Hover Power and Density Altitude

A helicopter close to a flat surface benefits from **ground effect**. As it climbs clear of that effect, it generally takes more power to hold the same stationary hover. A warmer day, a higher field elevation or a heavier aircraft can also change the power required. You can see how strongly your installed flight model responds by changing one condition at a time.

## What to record

Use **AGL** (height above the ground) to describe the hover and **MSL** (height above mean sea level) to describe the field. At an airport 5,000 ft above sea level, a helicopter can sit on the pad at about 5,000 ft MSL with zero ground clearance. An altimeter reading of 5,000 ft by itself says nothing about ground effect.

For each run, record field elevation, air temperature, pressure setting, wind, starting gross weight and the height being compared. On the engine display, note torque for both engines and the rotor-speed indication once the helicopter has settled. Keep each engine's torque reading separate so you can compare the same indication from one run to the next.

| Pair of runs | Change | Keep the same |
| --- | --- | --- |
| Low hover / higher hover | Height over the same level surface | Weather, load, helicopter and location |
| Cool day / warm day | Outside air temperature at one field | Pressure, wind, weight and hover height |
| Light cabin / heavier cabin | Weight at the centerline cargo station | Location, weather and hover height |

## Reading the comparison

If torque rises as you leave the surface and rotor speed stays steady, the second hover is using more power. If rotor speed or height changes throughout a run, you are comparing a transition with a hover. Repeat the sample after the height settles.

**Density altitude** describes the altitude in the standard atmosphere at which air has the same density as the air around the aircraft. Warmer air at the same pressure gives a higher density altitude. Two runs at the same field elevation can therefore give different results. Turn off live weather for this comparison and restore the initial fuel quantity between runs.

A useful entry in your flight notes is “same load, same pad, 10 °C warmer, torque changed by X percentage points.” For example, 64% to 68% is a change of **four percentage points**. A single pair of sim readings describes those two conditions. Repeat at other loads before using that observation to plan another flight.

[H-60 flight model](https://github.com/Delta-Simulations/MSFS-H-60M/blob/a403200d72edbfb01cfe243c0c05afc6e596882f/PackageSources/Simobjects/Airplanes/UH60/flight_model.cfg) · [Flight model reference fields](https://docs.flightsimulator.com/html/Content_Configuration/SimObjects/Aircraft_SimO/flight_model_cfg.htm)
