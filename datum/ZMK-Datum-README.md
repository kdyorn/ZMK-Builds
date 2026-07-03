# Datum — ZMK Build

A custom 86-key wireless split mechanical keyboard designed and built by [kdyorn](https://github.com/kdyorn).

## Overview

| Feature | Detail |
|---|---|
| Layout | 86-key split |
| Firmware | ZMK |
| Controller | Pro Micro nRF52840 |
| Battery | LiPo 3.7v 350mAh (per half) |
| Case | 3D Printed — Sunlu Matte PLA |
| Switches | GK Gamakay Pegasus Tactile |
| Connection | Wireless (Bluetooth) |

## Repository Structure

```
datum/
├── BOM.md              # Full bill of materials with links
├── firmware/
│   └── config/         # ZMK keymap and config files
├── case/
│   ├── stl/            # Print-ready STL files
│   └── source/         # Editable CAD source files
├── pcb/
│   └── gerbers/        # PCB production files
└── docs/
    └── build-photos/   # Build log photos
```

## Bill of Materials

See [BOM.md](BOM.md) for a full parts list with Amazon links.

## Build Notes

- Handwired build using 16 AWG copper wire for row bus bars and 22 AWG solid wire for column bus
- 26 AWG stranded wire used for controller connections
- Wheel weights added inside case for improved feel and stability
- JST PH2 2.0mm connectors used for battery connections

## License

This design is licensed under [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).

You are free to share and adapt this design for non-commercial purposes with appropriate credit to **kdyorn**.
