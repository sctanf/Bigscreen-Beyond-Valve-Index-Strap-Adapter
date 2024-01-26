Repo for making an Index strap fit on a Beyond, ~~maybe~~ with working audio.

- Pi Pico DAC - https://github.com/sctanf/picoamp
- Recommended pogo pin is 9.5mm unloaded and 7.5mm loaded, 2.54mm pitch. Or refer to the diagram below. You can cut a 6pin version in half for each side. You can push out the middle pin from the springloaded side, if you prefer.

## Installation
1. Print a left and right side adapter in the original orientation with supports
- Non reversed version has the cable exiting towards the head, reversed version exits towards the front
- If it fits too loosely, you can put a few layers of electrical tape covering the Beyond's knob to add some resistance
- If you do not use the pogo pins and/or do not need Index audio, you can screw in the adapters now (step 3)
2. Feed 24-28ga wires through the adapter and solder the pogo pins
- Positive side is toward the head, negative side is toward the front
- Solder wires on the inside side of the pins so it fits inside the adapter
- For non reversed adapters, negative wire should extend a bit farther so it folds flat inside the adapter
- This can be done in any order but it may be a good idea to have pre-cut wire lengths and already wired to a plug or to picoamp
3. Press in the header and screw the adapters into the Index strap
- The tolerance should be very tight for a standard printer, if it does not fit try to trim the print a little bit
- You can reuse the screws from the Index or use equivalent screws
4. Connect to a DAC
- Again positive side is toward the head, negative side is toward the front, remember to check how the wires were folded in the adapter
- The intention is to use picoamp, but any sufficiently powerful DAC can be used, you ideally need around or at least 1W for ~6ohm impedance
- Usually a headphone DAC provides much less power than theoretical at these lower impedance, but something rated at least 200mW for 32ohms should work, ymmv
- For some common DACs or for software EQ there are a few presets and extra notes under [eq folder](../../tree/main/eq) and [picoamp](https://github.com/sctanf/picoamp) repository if needed

![Beyond with an Index strap](../../blob/main/images/DSC_0445.jpg)

![pogo pins](../../blob/main/images/pogo.jpg)

![Index mount drawings](../../blob/main/images/index_strap_connectors.png)
