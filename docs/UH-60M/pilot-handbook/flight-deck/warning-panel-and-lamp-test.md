# Warning Panel and Lamp Test

During a parking-spot start, a powered warning panel can show **#1 ENG OUT**, **#2 ENG OUT** and **LOW ROTOR R.P.M.** together. Delta's [Cockpit Equipment Checks](../../Procedures/Cockpit%20Equipment%20Checks.md) list this combination while the engines are still stopped.

| Indication | What drives the cockpit lamp in V5.2.4 |
| --- | --- |
| **#1 ENG OUT** | The simulator reports no combustion in engine 1. |
| **#2 ENG OUT** | The simulator reports no combustion in engine 2. The two lamps have separate inputs. |
| **LOW ROTOR R.P.M.** | The cockpit model flashes this lamp when simulated main rotor speed is below its programmed threshold. The lamp reads rotor speed independently of the two engine lamps. |

## Reading the panel during startup

Watch what changes as the aircraft state changes. An engine lamp can clear while the rotor is still coming up to speed. The three lights tell you about two engines and one rotor, so they need not clear together. Use the engine instruments for the actual readings.

The button labeled **LAMPS TEST** in the checklist has the cockpit tooltip **TEST ANNUN**. A click toggles the lamp-test state in this version. If several lamps stay illuminated after you've checked them, click again to leave the test and read the panel under its normal conditions.

For a repeatable comparison, load the same variant at the same parking spot. Record the lights you see before startup and again after the sim's [engine runup](../../Procedures/Starting%20Engines.md#engine-runup). Include the spawn state and whether lamp test was selected when reporting a panel discrepancy.
