# double-sampling-PLL

> [!IMPORTANT]
> This repository requires the [IIC-OSIC-TOOLS](https://github.com/iic-jku/IIC-OSIC-TOOLS) container with tag `2026.08` or later.

## Chip Documentation

A designer-oriented description of this chip can be found in [doc/](doc/):

- **[doc/specifications.md](doc/specifications.md)**: top-level specifications (technology, supplies, clock, macro inventory, functional behaviour).
- **[doc/pinout.md](doc/pinout.md)**: full 32-pad bondpad table per side, with the `chip_top` port and the role each pad carries inside `chip_core`.
- **[doc/floorplan.md](doc/floorplan.md)**: die / core geometry, hard-macro placement coordinates, PDN strategy and the floorplan diagram.

## Directory Structure

```text
📁 template/
├─ 📁 doc/
│  ├─ 📁 PDK/
│  ├─ 📁 proposals/
│  ├─ 📁 klayout/
│  ├─ 📁 sizing/
│  ├─ floorplan.md
│  ├─ pinout.md
│  └─ specifications.md
├─ 📁 flow/
│  ├─ 📁
```

## Layout Versus Schematic (LVS)

## Design Rule Check (DRC)

## Parasitic Extraction (PEX)

## Acknowledgements
