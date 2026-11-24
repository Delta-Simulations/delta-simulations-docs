# Crew Alerts and Test Indications

Read the exact message on EICAS and note when it appeared. A cold helicopter, an active lamp test, and a running helicopter can show different combinations of indications on the same screen. Some labels read live MSFS values, others follow a scripted test, and some have a fixed inactive state.

| EICAS message | What drives it |
| --- | --- |
| **ENG 1/2 STARTER ON** | The matching engine's starter-active flag. Compare the engine number with the side being started. |
| **ENG 1/2 OIL PRESS**, **ENG 1/2 OIL HOT** | Each side reads its own simulated oil pressure or temperature. A stopped engine can show low pressure. |
| **BATT LOW CHARGE** | Either main battery is below the voltage threshold used by the instrument. The caption does not identify the lower battery. |
| **MAIN XMSN PRESS** | This message follows modeled rotor speed. The display uses rotor speed as a proxy for this caption. |
| **T/R SERVO 1 FAIL**, **BACKUP RSVR LOW** | The hydraulic leak-test flag turns these messages on during the scripted sequence. |
| **ICE DETECTED**, **APU OIL HOT** | These particular EICAS entries have fixed inactive conditions. A quiet message list provides no measurement of ice or APU oil temperature. |

## Reading a parked helicopter

With displays powered and engines stopped, look at the engine indications alongside the caution columns. During a start, note which starter message changes first and whether the engine readouts change on the same side. When comparing two screenshots, match the start state as well as the position of the switches.

The master-panel lamp test checks the annunciator lamps. The [hydraulic leak test](../power-and-fuel/hydraulic-leak-test-indications.md) drives a separate set of messages. After a test finishes, read EICAS again before treating a message captured during the test as a persistent fault. The left and right caution lists each draw up to six active entries in a fixed order, so a crowded column can hide lower entries.

For an unexpected indication, capture the entire EICAS, the exact message text, the spawn location type, and the last control used. Include the aircraft and simulator versions when you report it. These details let another pilot reproduce the display state. A real-aircraft emergency response cannot be inferred from one of these simulated messages.

[Left caution list](https://github.com/Delta-Simulations/MSFS-H-60M/blob/a403200d72edbfb01cfe243c0c05afc6e596882f/src/instruments/src/PFD/Components/EICAS/CASAlerts/CASWarningsLH.tsx) · [Right caution list](https://github.com/Delta-Simulations/MSFS-H-60M/blob/a403200d72edbfb01cfe243c0c05afc6e596882f/src/instruments/src/PFD/Components/EICAS/CASAlerts/CASWarningsRH.tsx)
