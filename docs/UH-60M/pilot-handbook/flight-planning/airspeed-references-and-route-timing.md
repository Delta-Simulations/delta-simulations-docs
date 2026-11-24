# Airspeed References and Route Timing

Three speed readings answer different questions during a cross-country flight.

| Reading | Unit | Use in the sim |
| --- | --- | --- |
| Indicated airspeed | KIAS | Read it on the cockpit airspeed scale and compare it with indicated-speed markings. |
| True airspeed | KTAS | Use it for motion through the airmass. At altitude, true and indicated airspeed can differ. |
| Groundspeed | kt | Use it with remaining track distance in nautical miles to calculate an arrival time. |

In the flight model, the **cruise reference is 100 KTAS** and the **maximum indicated speed field is 140 KIAS**. Microsoft uses reference-speed fields for features such as aircraft selection and speed indications. These entries describe the add-on configuration. A published cruise reference alone cannot predict your groundspeed or fuel burn.

## Time a leg with the wind

Suppose a leg is **60 NM** long. For a simple estimate, use 100 KTAS and assume the wind is directly along the route. With a crosswind, use the actual groundspeed along your planned track.

| Wind component | Estimated groundspeed | Time for 60 NM |
| --- | ---: | ---: |
| Calm | 100 kt | 36 min |
| 20 kt headwind | 80 kt | 45 min |
| 20 kt tailwind | 120 kt | 30 min |

The calculation is **minutes = 60 × distance in NM ÷ groundspeed in kt**. A 60 NM outbound leg at 80 kt followed by a 60 NM return at 120 kt takes **75 minutes** altogether. Averaging the two speeds gives 100 kt and a 72-minute estimate, which comes up short because the slower leg takes longer.

Once in cruise, recalculate from the distance still to go and the groundspeed you actually see. If 24 NM remain at 80 kt, the new estimate is **18 minutes**. Add time for anything the distance-to-destination readout doesn't include, such as an arrival circuit or a stop along the way. For fuel planning, apply the measured total burn in your own simulator to each leg's elapsed time.

[H-60 flight model](https://github.com/Delta-Simulations/MSFS-H-60M/blob/a403200d72edbfb01cfe243c0c05afc6e596882f/PackageSources/Simobjects/Airplanes/UH60/flight_model.cfg) · [Flight model reference fields](https://docs.flightsimulator.com/html/Content_Configuration/SimObjects/Aircraft_SimO/flight_model_cfg.htm)
