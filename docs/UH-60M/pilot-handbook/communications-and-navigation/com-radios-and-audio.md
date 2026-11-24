# COM Radios and Audio Selection

COM1 and COM2 each have an active frequency and a standby frequency in the Delta H-60. The active frequency determines which station you can hear. The transmit selector determines which radio carries your voice. You can tune COM2 correctly and still transmit on COM1.

## Tune a radio

1. Bring the helicopter's electrical system online. If the cockpit is dark, use the [electrical power guide](../power-and-fuel/batteries-generators-and-display-power.md) before troubleshooting the audio.
2. On a hardware radio panel or in your MSFS controls, select COM1 or COM2. Set the standby frequency. The whole-number and fractional controls adjust different parts of the frequency.
3. Transfer standby to active on that **same radio**. Check the digits again after transfer. On a panel that shows both frequencies, the old active frequency should now appear in standby.
4. Select the desired radio for transmit. Set the receive selector and audio output so you can hear it. Listening to a second frequency leaves the original transmit selection in place.

The add-on declares two COM radios with standby tuning. Several keys on the modeled pedestal keypad have no cockpit action. If a keypad press has no effect, use the corresponding MSFS COM command or a radio panel that reads the simulator's active frequency.

## Flying on VATSIM with vPilot

Set your headset output, microphone and push-to-talk button in vPilot. Speak at normal volume and check the microphone meter in its audio settings. Then compare vPilot's frequency and transmit selection with your intended station before calling.

| In the vPilot message box | Result |
| --- | --- |
| `.com1 FREQUENCY` or `.com2 FREQUENCY` | Tunes the named radio. Substitute the frequency published for the station. |
| `.com 1` or `.com 2` | Selects the radio used for transmit. |
| `.com both` | Toggles reception on both radios. Check the receive indicators after using it. |

For a handoff, leave the current controller on COM1, tune the next controller on COM2, then switch transmit when instructed. If you can hear the new controller but they cannot hear you, check which radio has **TX** before changing the frequency again. If the TX selection is correct, check push-to-talk and the microphone meter separately.

[H-60 radio configuration](https://github.com/Delta-Simulations/MSFS-H-60M/blob/a403200d72edbfb01cfe243c0c05afc6e596882f/PackageSources/Simobjects/Airplanes/UH60/systems.cfg) · [vPilot audio, transmit selection and commands](https://vpilot.rosscarlson.dev/Documentation)
