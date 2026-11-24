# Hydraulic Leak Test Indications

The overhead **HYD LEAK TEST** switch lets you exercise a group of hydraulic messages on EICAS while parked. It has three positions, **TEST**, **NORM** and **RESET**. The add-on registers a new test when MSFS reports that the helicopter is on the ground.

## What the display shows

| EICAS area | Messages produced by the test |
| --- | --- |
| Upper left and upper right | **RSVR 1 LOW** and **RSVR 2 LOW** |
| Left caution area | **T/R SERVO 1 FAIL** and **BACKUP RSVR LOW** |
| Advisory box | **BACK UP PUMP ON** and **T/R SERVO 2 ON** |

**RSVR** refers to a reservoir and **T/R** to the tail rotor. The number belongs to the system named on that line. For example, **RSVR 2 LOW** refers to reservoir 2, while **T/R SERVO 2 ON** refers to the second tail rotor servo. More than one advisory page can be active when the aircraft also has electrical, lighting or fuel pump advisories.

## Why messages stay up at NORM

In the parked cockpit, selecting **TEST** sets the test state. Moving the switch back to **NORM** leaves that state latched. Select **RESET** to clear the test, then return the switch to **NORM**. The group of test messages should disappear together. A generator or engine oil message that remains belongs to a different system.

This difference is useful when troubleshooting a saved session. If both reservoir cautions and the two tail rotor servo messages appear together after you've used the switch, check the test state first. The add-on generates that group from a single test input. The messages alone do not establish that MSFS has simulated fluid loss in multiple systems.

[H-60 systems source](https://github.com/Delta-Simulations/MSFS-H-60M/tree/a403200d72edbfb01cfe243c0c05afc6e596882f/PackageSources/Simobjects/Airplanes/UH60)
