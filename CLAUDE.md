# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

OpenFormicaria is an open-source modular 3D-printable ant formicarium (ant nest) system. It is a hardware/CAD design project, not a software project. The primary artifacts are FreeCAD CAD files (`.FCStd`) and exported STL files for 3D printing.

## Commands

**Build distribution packages:**

```bash
python package.py
```

Creates `connectors.zip`, `modules.zip`, and `formicaria.zip` in a `package/` directory, each containing the relevant STL files and documentation.

**Serve documentation locally:**

```bash
pip install -r requirements.txt
mkdocs serve
```

Documentation is built with MkDocs + Material theme and deployed at [https://of.schemen.me](https://of.schemen.me).

## Repository Structure

```text
Connectors/   - Standalone connector pieces between modules
Modules/      - Portal and Gateway modules (4xGateway, 6xGateway)
Formicaria/   - Ant nest chamber templates with species-specific inserts
Measurements/ - Technical spec images for connector dimensions
docs/         - MkDocs documentation source
```

Each hardware category follows the pattern `Category/CAD/` (FreeCAD source files) and `Category/STL/` (exported 3D-printable models).

## Design Standards

**Base grid:** All connector-facing module faces are based on a **35×35×20mm** block. The 4xGateway is exactly this size; the 6xGateway is 35×70mm (two connector placements per side).

**Connectors:** All connectors use the CV2 standard. CV2 females have a center Hill; CV2 males have a Rail+Groove for the Hill to slide and lock. All connectors must be printed in flexible filament (TPU/Flex). Refer to images in `Measurements/` for exact specs.

**Module specs:**

- Glass cutout: 3mm deep
- M3 screw holes: 1.4mm radius
- Ant cutout: ~15mm deep (leaves 2mm floor at 20mm total height)
- Glass ledge: 1mm wide

**Formicaria workflow:**

1. A blank template (no ant pathways) is maintained per size and exported as STL.
2. A black/white ant pathway design is drawn in Photoshop (PSD templates in `Formicaria/Inserts/`) and combined with the template in 3D Builder to produce the final insert STL.

## Contributing

- Create PRs into the **`devel`** branch (not `master`).
- Use an existing CAD file as reference; all new designs must follow the CV2 connector standard.
- New parts must include STL exports in the correct `STL/` subfolder, CAD source in the correct `CAD/` subfolder, and documentation in `docs/`.
