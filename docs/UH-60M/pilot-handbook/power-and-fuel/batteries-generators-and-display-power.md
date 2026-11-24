# Batteries, Generators and Display Power

The add-on models three electrical buses. Both main batteries, both engine generators, the APU generator and external power connect to the hot battery bus. That bus connects to the main and essential avionics buses. The standby instrument battery has its own connection to the essential avionics bus.

| Bus | Examples in the add-on |
| --- | --- |
| Main | The general panel, radios, engine starter controls, electric fuel pumps and most lighting circuits. |
| Hot battery | Connection point for the main batteries, generators and external power. |
| Essential avionics | The standby instrument circuit and standby battery. |

## Operating the overhead switches

The battery and generator controls have separate mouse targets for the normal position and the momentary test position. With tooltips enabled you may see the same switch name over both targets. The test target shows an up-arrow cursor and springs back when released. The normal target shows a down-arrow cursor. For a battery check, hold the test position while you look for **BATT GOOD** or **BATT LOW**. To power the cockpit, select the normal ON position.

**BATT STBY INST** arms a separate supply. The add-on brings this battery online when the main bus loses power. The two engine generators have individual switches, **ENG1 GEN** and **ENG2 GEN**. EICAS can report **GEN 1 FAIL** or **GEN 2 FAIL** if that generator is switched off or its output is low. Seeing these messages with the engines stopped is consistent with the starting state.

## One MFD is on and another is dark

Each MFD has its own power button. In version 5.2.4, MFD 2 can power up at a lower main-bus voltage than MFDs 1 and 3. One lit display on battery power can therefore be normal. Once the APU or engine generators are supplying power, check the power button on each remaining display.

**APU GEN ON** confirms that the APU generator is active. **EXT PWR CONNECTED** reports the simulator's external power state. If you're comparing starts at different parking spots, note which of those advisories you have before changing any settings.

[V5.2.4 aircraft systems](https://github.com/Delta-Simulations/MSFS-H-60M/tree/V5.2.4/PackageSources/Simobjects/Airplanes/UH60)
