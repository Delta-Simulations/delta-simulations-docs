# Aircraft Limits and Reference Speeds

The stock UH-60M flight model supplies values for the simulator's load and speed fields. These fields use several different units. Read the field name before comparing a number on the aircraft-selection screen with a cockpit indication.

| V5.2.4 field | Stock UH-60M value | Where it matters |
| --- | ---: | --- |
| Empty weight | 12,511 lb | Starting point for adding crew, cargo and fuel. |
| Maximum gross weight | 23,000 lb | Compare with the **loaded** aircraft weight in the simulator's weight and balance screen. |
| Reference cruise speed | 100 KTAS | A planning reference in true airspeed. Wind changes how quickly the aircraft covers a ground track. |
| Maximum indicated speed | 140 KIAS | The flight-model reference labeled as a red line, expressed in indicated airspeed. |
| Airspeed indicator maximum | 170 kt | The upper extent configured for the instrument scale. It is a separate value from the indicated-speed reference. |

## Before comparing two figures

Start with the aircraft title. A figure from a different H-60 variant, or a real-aircraft specification expressed in miles per hour, makes a poor comparison with an indicated reading from this model. Check the speed type next. A groundspeed reading above or below 100 kt alone says little about whether you are flying at the configured cruise reference. The [airspeed and route timing examples](airspeed-references-and-route-timing.md) show how a wind changes the result over a full round trip.

A load under the configured gross-weight figure can still produce an aft or lateral imbalance. Read the [station positions](cabin-loading-and-center-of-gravity.md) when a change in cargo affects the amount of cyclic needed. A helicopter at the same weight can also need more hover power after you change the weather or the altitude of the starting pad.

## Comparing a saved flight with the stock aircraft

Record the selected variant, total weight, fuel units, field elevation and weather. Use the same departure and payload for a second flight. If a cockpit gauge goes past the number you expected, record which gauge it was, its units and whether the value came from a moving pointer, digital window, configuration field or an actual warning. The released model supplies no single performance figure that accounts for all of those conditions.

[Stock UH-60M weight and reference-speed fields](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/PackageSources/Simobjects/Airplanes/UH60/flight_model.cfg) · [Gross weight and payload stations](gross-weight-and-payload-stations.md)
