# How to Contribute

All contributions are welcome. Use an existing CAD file as reference when creating new parts — all new designs must follow the CV2 connector standard.

Fork the repository on [GitHub](https://github.com/schemen/OpenFormicaria), make your changes, and open a pull request into the **`devel`** branch (not `master`).

When submitting, make sure your PR includes:

- STL exports in the correct `STL/` subfolder (`Connectors/STL/`, `Modules/STL/`, `Formicaria/STL/`)
- CAD source files in the correct `CAD/` subfolder
- Documentation for your part in the `docs/` folder

---

## Design Standards

### Base Grid

All connector-facing module faces must follow the **35×35×20mm base grid**. The 4xGateway is exactly one base unit; the 6xGateway is two units wide (70×35mm). Faces that don't carry connectors (such as the Portal's feeder face) can deviate from this grid.

### Module Specs

- Glass cutout depth: **3mm**
- M3 screw hole radius: **1.4mm**
- Ant interior depth: **~15mm** (leaves a 2mm floor at 20mm total height)
- Glass ledge width: **1mm**

### CV2 Connector Specs

The female port is built into every module face. The standalone connector is the male piece inserted between two ports.

- Female port: central hole radius **5mm**, centered on the face, with a **Hill** in the center — see `Measurements/ConnectorV2_Hill.PNG` for dimensions
- Male connector: has a **Rail** and **Groove** that slides over the Hill and locks — see `Measurements/ConnectorV2_Rail.PNG` and `Measurements/ConnectorV2_Groove.PNG`
- Full cut and gate measurements: `Measurements/Connector Cut Measurements.png`, `Measurements/Connector Gate Measurements.png`

---

## Creating a New Formicarium Insert

Inserts are created in two steps: design a black-and-white tunnel layout image, then combine it with the blank template STL in Microsoft 3D Builder to produce the final insert STL.

**Source files:**

- Blank template STLs: `Formicaria/STL/CV2/CV2_OF_Formicarium_Template_S.stl` and `CV2_OF_Formicarium_Template_M.stl`
- PSD templates (sized to match the interior footprint): `Formicaria/Inserts/`
- Existing insert examples to reference: `Formicaria/Inserts/Lasius_size_s.psd`, `Lasius_size_m.psd`

**Workflow:**

1. Open the PSD template for your target size in Photoshop or a compatible editor
2. Draw your tunnel and chamber layout — black areas become carved-out voids, white areas remain solid
3. Export the design as a flat image (PNG)
4. In Microsoft 3D Builder, import the blank template STL and combine it with your image to extrude the tunnel pattern into the nest body
5. Export the result as an STL

**When submitting:**

- Name your STL using the existing convention: `CV2_OF_Formicarium_<Species>_<Size>.stl` (e.g. `CV2_OF_Formicarium_Camponotus_S.stl`)
- Place the STL in `Formicaria/STL/CV2/`
- Place your PSD/source image in `Formicaria/Inserts/`
- Add a description and image to `docs/formicaria.md` under the relevant size section

See [Formicaria](formicaria.md#custom-inserts) for the user-facing description of this workflow.

---

## Supporting the Project

If you find the project useful, consider supporting the original author on [Buy Me a Coffee](https://www.buymeacoffee.com/schemen).
