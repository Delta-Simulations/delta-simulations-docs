# Bleed Air and Ground Power

Three overhead selections often get confused during a parked start. **APU CONT** runs the auxiliary power unit. **GENERATORS APU** connects its electrical output. **AIR SCE HT/STRT** selects the compressed air source used for heating and starting. Getting a screen to light establishes an electrical supply, but tells you nothing about the position of the air selector.

## Overhead controls

| Control | What changes in the add-on |
| --- | --- |
| **AIR SCE HT/STRT – ENGINE** | Selects the modeled engine bleed-air source. |
| **AIR SCE HT/STRT – OFF** | Clears the engine and APU bleed-source selections in the system logic. |
| **AIR SCE HT/STRT – APU** | Selects the simulator APU bleed-air source. APU generator selection remains independent. |
| **EXT PWR** | Requests the simulator's external electrical power connection. It does not select a pneumatic source. |
| **GENERATORS APU** | Commands the APU generator. Look for the corresponding EICAS advisory once power is available. |

## Compare two parked starts

On a cold apron start, follow [Before Start](../../Procedures/Before_Start.md) and [Cockpit Equipment Checks](../../Procedures/Cockpit%20Equipment%20Checks.md). Watch for **APU ON** and **APU GEN ON** separately on EICAS. The first advisory follows APU speed. The generator advisory follows the electrical generator state. If you only see the first, check the generator switch and individual MFD power before interpreting the dark instrument as a failed start.

If you normally start with the engines already running, the [start-state comparison](apron-and-airborne-start-states.md) identifies what MSFS has already set. Re-create a reported issue with the same start state and power source. A difference between an airborne spawn and a cold apron start can otherwise mask the missing control.

The heater and blower are downstream cabin controls. Changing the air source alone does not set a cabin temperature. For the distinction between warm air and ambient ventilation, see [cabin heating and ventilation](../airframe-and-instruments/cabin-heating-and-ventilation.md).

[Engine and air-source logic](https://github.com/Delta-Simulations/MSFS-H-60M/blob/a403200d72edbfb01cfe243c0c05afc6e596882f/PackageSources/Simobjects/Airplanes/UH60/Panel/Systems/ENG_SYS.xml) · [EICAS advisory inputs](https://github.com/Delta-Simulations/MSFS-H-60M/blob/a403200d72edbfb01cfe243c0c05afc6e596882f/src/instruments/src/PFD/Components/EICAS/CASAlerts/CASAdvisory.tsx)
