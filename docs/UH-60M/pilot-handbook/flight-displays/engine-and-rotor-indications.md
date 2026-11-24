# Engine and Rotor Indications

Select **EICAS** on the bottom bezel. The engine indications are grouped around the central rotor-speed indication. Read the label as well as the number. Several neighboring instruments use percentages but measure different things.

| Label | Quantity | Units |
| --- | --- | --- |
| **Q** | Engine torque | Percent |
| **NG** | Gas generator speed | Percent |
| **TGT** | Turbine gas temperature | Degrees Celsius |
| **NP1**, **NP2** | Power turbine speed for the numbered engine | Percent |
| **NR** | Main rotor speed | Percent |
| Engine oil temperature and pressure | Oil temperature and pressure for the engine | Degrees Celsius and psi, respectively |

The **Q** and **NR** indications answer different questions. Q shows how much torque an engine is delivering. NR shows how fast the rotor is turning. When comparing two screenshots or reporting an instrument issue, include the label and unit along with the reading.

## Comparing the engines

V5.2.4 feeds both sets of EICAS engine tapes from engine 1. That includes torque, NG, TGT, NP, and oil temperature and pressure. The two sides can move together even when you change only one engine in the simulator. The **Q1** and **Q2** readouts on the PFD use separate engine torque inputs and offer another place to check what the sim is reporting.

## Fuel on EICAS

The **MAIN FUEL** indications show tank 1 and tank 2 by weight in pounds. **TOTAL** uses the simulator's total fuel weight. Each number rounds down to the nearest five pounds, so the two displayed tank values can add up to slightly less than the displayed total even with only the main tanks aboard.

[V5.2.4 instrument reference](https://github.com/Delta-Simulations/MSFS-H-60M/blob/V5.2.4/src/instruments/src/PFD/Components/EICAS/EICASTapes.tsx)
