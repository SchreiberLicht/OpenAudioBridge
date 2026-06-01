# OpenAudioBridge

OpenAudioBridge is an open hardware + firmware project aimed at replacing outdated FireWire audio interfaces in older analog mixers with modern USB audio.

The main target is the FireWire expansion card of the Mackie Onyx 1640 mixer. The goal is a direct replacement module that fits into the original slot and works without any modifications to the mixer.

---

## What this is about

A lot of older analog mixers are still perfectly usable and quiet nice to mix with, but the FireWire interfaces which added nice features like multi track recordings are either dead, unsupported or hard to replace.

This project tries to fix that by building a modern USB-based replacement that behaves like the original interface.

---

## Target (for now)

- Mackie Onyx 1640 FireWire expansion card replacement
- 18 outputs / 2 inputs (16 cannel + main R&L out + 2 in)
- internal drop-in module (no case mods, no rewiring)
- USB audio interface 

---

## Approach

The design (till now) is based on an XMOS XU316 USB audio processor with external ADC/DAC stages.

---

## Long term idea

If this works, it could become a more general platform for replacing legacy FireWire interfaces in other mixers.

But right now the focus is only the Onyx 1640.

---

## Status

Nothing is built yet.  
Right now: reverse engineering / early design phase

---

## License

Hardware: CERN-OHL-S v2  
Firmware: MIT
