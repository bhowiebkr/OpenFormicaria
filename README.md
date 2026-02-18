# OpenFormicaria

An open-source modular ant formicarium system with interchangeable, space-saving connectors. Every part is compatible with every other part — from a small Portal for founding colonies all the way up to interconnected formicaria for large colonies.

![Example Farm](docs/img/1.jpg)

---

## Documentation

| Page | Description |
| --- | --- |
| [Getting Started](docs/getting_started.md) | What to print first, required materials, and starter kit lists |
| [Ant Species Guide](docs/ant_species.md) | Which ant species work well with this system and minimum size requirements |
| [Connectors](docs/connectors.md) | Every connector type explained — when to use each one |
| [Modules](docs/modules.md) | Portal and Gateway outworld modules |
| [Formicaria](docs/formicaria.md) | Nest chambers — sizes, inserts, heating, and humidity |
| [How to Contribute](docs/contrib.md) | Design standards, connector specs, and how to submit new parts |
| [Tips & References](docs/research_notes.md) | Supplementary care tips, filament advice, and community references |

---

## How It Works

OpenFormicaria is built around a **35×35×20mm base grid**. Any connector-facing face follows this grid, meaning all modules, gateways, and formicaria can connect to each other freely. The 4xGateway is exactly one base unit (35×35mm); the 6xGateway is two units wide (70×35mm).

All connectors use the CV2 system. They feature a Hill/Rail/Groove locking mechanism that allows connectors to be swapped while in use — so you can block or open passages between modules without losing any ants. **All connectors must be printed in TPU or flexible filament.**

---

## Parts Overview

### Connectors

All connectors fit the same female socket on every module. **Print all connectors in TPU or flexible filament** at 0.2mm layer height, 15% infill. Tube connectors require supports; everything else prints without.

| Part | Description |
| --- | --- |
| **Main Connector** | Joins two modules together |
| **Connector Blocker** | Same form factor as Main Connector but blocks the passage |
| **Blocking Endpoint** | Decorative dead-end cap for unused ports |
| **Tube Connector** (straight) | Connects 10mm, 12mm, or 14mm tubes — tube fits over the connector |
| **Tube Connector** (90°) | Same as above but at a right angle |
| **Connector Raiser** | Bridges the height difference between a module and a formicarium basin |
| **Separator** | Splits two connected modules and blocks both entries simultaneously |

---

### Modules

All modules print in PLA or any hard filament at 0.2mm layer height and 15% infill. Each module requires a piece of plexiglass for the viewing window (press-fit or M3 screw holes optional).

| Module | Outer Size | Ports | Plexiglass |
| --- | --- | --- | --- |
| **Portal** | 70×40×20mm | 4 | 26×62×2mm |
| **4xGateway** | 35×35×20mm | 4 | 27×27×2mm |
| **6xGateway** | 70×35×20mm | 6 | 62×27×2mm |

**Portal** — The starting module. Connect your founding test tube here. Features two feeding holes (lids should be printed in TPU to press-fit properly), air vents, and a cover lid.

**4xGateway** — Compact hub for branching your layout in any direction.

**6xGateway** — Wider hub with air vents for larger colony setups needing more connection points.

> Tip: Print modules in a colour that contrasts with your ants so you can spot them easily.

---

### Formicaria (Nest Chambers)

Each formicarium is a three-part assembly: an **insert** (the nest body the ants live in, with tunnels and chambers), a **basin** (slides underneath — holds the water reservoir and heat cable channel), and a **lid** (covers the top to keep the interior dark). The insert is printed separately from the basin, so you can swap in different tunnel layouts for different species without reprinting everything.

| Size | Outer Size | Plexiglass |
| --- | --- | --- |
| **S** | 70×80×20mm | 62×62mm |
| **M** | 105×115×20mm | 97×97mm |

Available inserts:

- **Lasius S / Lasius M** — Tunnel layout optimised for Lasius species
- **Blank template** — Design your own insert in any image editor and combine it with the template in Microsoft 3D Builder

Don't forget to print both the basin and the lid for your chosen size.

---

## Materials You Need

### 3D Printing Filament

- **Hard filament** (PLA, PETG, or similar) — for all modules and formicaria
- **Flexible filament** (TPU, Flex, or similar) — required for all connectors; also recommended for Portal feeder lids

### Plexiglass / Acrylic Sheet (2mm thick)

Cut to size for whichever parts you print:

| Part | Glass size |
| --- | --- |
| Portal | 26×62mm |
| 4xGateway | 27×27mm |
| 6xGateway | 62×27mm |
| Formicaria S | 62×62mm |
| Formicaria M | 97×97mm |

### Hardware

- **M3 screws** — optional, for screwing plexiglass in place instead of press-fitting
- **M3 heat set inserts (brass)** — optional upgrade; press one into each screw hole with a soldering iron before fitting the plexiglass. The brass threads are significantly more durable than threading directly into the printed plastic, making this worthwhile if you plan to remove and refit the plexiglass panels regularly for cleaning or maintenance.

### Tubing (optional)

Straight and angled tube connectors are available for 10mm, 12mm, and 14mm inner-diameter tubes if you want to run tubing between modules or to an outworld.

---

## Suggested Starter Sets

### Base Kit — First Outworld

Good for a founding colony transitioning out of a test tube.

- 1× Portal + 1× Portal Lid + 2× Portal Feeder Lids
- 26×62×2mm plexiglass for the Portal
- 2× Separators
- 3× Blocking Endpoints
- 2× Tube Connectors (sized to your test tube diameter)

### First Formicarium — Growing Colony

Add this once the colony needs a proper nest.

- 1× Size S Formicarium (basin + lid + insert)
- 62×62×2mm plexiglass
- 3× Blocking Endpoints (4× if connecting via tubes)
- 1× Connector Raiser (for direct connection to a Portal)
- or 1× Tube Connector (for tube connection)

---

## Where to Download

- **Printables:** [https://www.printables.com/model/45114-openformicaria-a-modular-ant-housing-platform](https://www.printables.com/model/45114-openformicaria-a-modular-ant-housing-platform)
- **Thingiverse:** [https://www.thingiverse.com/thing:4637707](https://www.thingiverse.com/thing:4637707)
- **GitHub (latest files):** [https://github.com/bhowiebkr/OpenFormicaria](https://github.com/bhowiebkr/OpenFormicaria) — STL files are in the `STL/` subfolder of each category (`Connectors/STL/`, `Modules/STL/`, `Formicaria/STL/`)

---

## About This Fork

This is a personal fork of the original OpenFormicaria project created by [schemen](https://github.com/schemen/OpenFormicaria). The upstream repository is the authoritative source for the latest designs and the official documentation at [https://of.schemen.me](https://of.schemen.me).

If you find the project useful, please consider supporting the original author on [Buy Me a Coffee](https://www.buymeacoffee.com/schemen) — it goes a long way toward motivating continued development.

## Contributing

See [How to Contribute](docs/contrib.md) for design standards, connector specifications, and folder conventions. Pull requests should target the **`devel`** branch.
