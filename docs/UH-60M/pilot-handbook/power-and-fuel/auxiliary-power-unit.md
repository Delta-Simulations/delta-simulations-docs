# Auxiliary Power Unit

The APU can supply electricity to the parked helicopter and bleed air for engine start. The overhead panel gives you separate controls for the APU itself, its generator, its fuel pump and the air source. That distinction matters when you can hear the APU but the cockpit still looks dark.

| Overhead control | What it does in the sim |
| --- | --- |
| **APU CONT** | Starts or stops the APU. The cockpit tooltip reads **APU CNTRL**. |
| **FUEL PUMP** | The **APU BOOST** position selects the APU's electric fuel pump. Its tooltip reads **PRIME APU**. This is a separate pump from the two engine boost pumps. |
| **GENERATORS APU** | Connects the APU generator when the unit can supply power. Its tooltip reads **APU GEN**. |
| **AIR SCE HT/STRT** | Selects the bleed-air source. The cockpit tooltips identify **ENGINE**, **OFF** and **APU**. |

## APU indications

Watch the overhead APU ON light as the unit spools up. Once EICAS is available, look for **APU ON** in the advisory box. The overhead light comes on slightly earlier than the EICAS message. **APU GEN ON** is a second advisory. It appears when MSFS reports that the generator is active.

If you see **APU ON** by itself, check the APU generator switch. Changing the air source selects bleed air. It will not bring a generator online. If you see both advisories but one MFD stays dark, check the power button on that screen. Each display has its own.

## APU fuel supply

The add-on draws APU fuel from the left main tank. If the APU will not start after you edit the fuel load in MSFS, check the left tank individually. The aircraft can show fuel in **TOTAL** with all of that fuel in the right tank. The APU needs fuel on its own side and electrical power for its starter and pump.

Use the [Cockpit Equipment Checks](https://docs.deltasimulations.ca/UH-60M/Procedures/Cockpit%20Equipment%20Checks/) for the normal parked startup sequence.

[H-60 systems source](https://github.com/Delta-Simulations/MSFS-H-60M/tree/a403200d72edbfb01cfe243c0c05afc6e596882f/PackageSources/Simobjects/Airplanes/UH60)
