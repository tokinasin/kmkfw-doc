---
title: Modules
nav_order: 3
---

# Modules
Modules, unlike extensions, change how your keyboard works. These are meant to have
the ability to alter the core code in any way. Unlike extensions, these are not in a
sandbox, and can make massive changes to normal operation.

## Core Modules
These modules are provided in all builds and can be enabled. Currently offered
modules are

- [Combos](/docs/modules/core/combos): Adds chords and sequences
- [Layers](/docs/modules/core/layers): Adds layer support (Fn key) to allow many more keys to be
put on your keyboard.
- [HoldTap](/docs/modules/core/holdtap): Adds support for augmented modifier keys to act as one key
when tapped, and modifier when held.
- [Macros](/docs/modules/core/macros): Adds macros.
- [Mouse keys](/docs/modules/core/mouse_keys): Adds mouse keycodes.
- [Sticky keys](/docs/modules/core/sticky_keys): Adds support for sticky keys.
- [Power](/docs/modules/core/power): Power saving features. This is mostly useful when on battery power.
- [Split](/docs/modules/core/split_keyboards): Keyboards split in two. Seems ergonomic!
- [SerialACE](/docs/modules/core/serialace): [DANGER - _see module README_] Arbitrary Code Execution over the data serial.
- [TapDance](/docs/modules/core/tapdance): Different key actions depending on how often it is pressed.
- [Dynamic Sequences](/docs/modules/core/dynamic_sequences): Records a sequence of keypresses and plays it back.

### Require Libraries
These modules can be used without specific hardware, but require additional libraries such as the `Adafruit CircuitPython Bundle`.

 - [MIDI](/docs/modules/core/midi): Adds sending MIDI data in the form of keymap entries.


### Peripherals
These modules are for specific hardware and may require additional libraries to function.
- [ADNS9800](/docs/modules/core/adns9800): Controlling ADNS9800 optical sensor.
- [Encoder](/docs/modules/core/encoder): Handling rotary encoders.
- [Pimoroni trackball](/docs/modules/core/pimoroni_trackball): Handling a small I2C trackball made by Pimoroni.
- [AS5013 aka EasyPoint](/docs/modules/core/easypoint): Handling a small I2C magnetic position sensor made by AMS.
