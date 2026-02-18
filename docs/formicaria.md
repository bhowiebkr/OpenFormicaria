# Formicaria

A formicarium is the **nest chamber** — the enclosed space where the ants actually live, raise brood, and house the queen. This is distinct from the [Modules](modules.md) (outworld/foraging spaces) and [Connectors](connectors.md) that link everything together.

Each formicarium is a three-part assembly:

1. **The insert** — the nest body itself, printed with ant tunnels and chambers carved into it. Sits in the middle.
2. **The basin** — slides underneath the insert. Holds water (for humidity) and routes the heat cable. The basin is what raises the formicarium slightly higher than a flat module like the Portal, which is why a [Connector Raiser](connectors.md#connector-raiser) is needed for direct side-by-side connections.
3. **The lid** — sits on top to keep the interior dark. Ants strongly prefer darkness for nesting.

The plexiglass panel presses into a slot on the front face, giving you a view into the tunnels without disturbing the colony.

## Print Settings

- 0.2mm layer height
- 15% infill
- PLA, PETG, or any hard filament
- Print the basin and lid in the same material as the insert

## Heating

The basin has a built-in channel for a heat cable. Route the cable through this channel on **one side only** — never all the way around. This creates a temperature gradient across the nest so ants can move between warmer brood-rearing zones and cooler resting areas, which is essential for healthy colony behaviour.

Always use a thermostat with your heating element to prevent overheating. For most temperate species (Lasius, Formica, Camponotus), target **20–26°C** on the warm side.

> Do not heat during winter if keeping a species that requires hibernation — this applies to most European species.

## Humidity

Fill the basin with water regularly. It evaporates slowly up through the nest body, passively humidifying the chambers — this is the primary water source for the colony.

- **Too dry:** Brood desiccates, ants appear lethargic, fewer eggs laid
- **Too wet / mould visible:** Reduce watering frequency; ants will relocate brood to drier areas if conditions worsen

---

## Formicaria Size S

The Size S is the starting nest for a small colony graduating from a test tube. It has room for a growing founding colony and connects directly into the rest of the system via CV2 ports.

**Dimensions:** 70mm × 80mm × 20mm

**Parts to print:**

- 1x Insert (`CV2_OF_Formicarium_<style>_S.stl`)
- 1x Basin (`OF_Formicarium_Basin_S.stl`)
- 1x Lid (`OF_Formicarium_Lid_S.stl`)

**Plexiglass:** 62mm × 62mm × 2mm. Can be press-fit or secured with M3 screws.

### Template S

![Template S](img/15.jpg)

A blank insert — no ant pathways. Use this as your starting point for designing a custom tunnel layout. See the [Custom Inserts](#custom-inserts) section below.

### Lasius S

![Lasius S](img/17.jpg)

A ready-to-print insert with tunnel and chamber layout suited to *Lasius* and similar shallow-nesting species. Good starting point for most beginners.

---

## Formicaria Size M

The Size M suits a colony that has outgrown the Size S — more floor area, more chambers, and more connector ports for expanding the setup further.

**Dimensions:** 105mm × 115mm × 20mm

**Parts to print:**

- 1x Insert (`CV2_OF_Formicarium_<style>_M.stl`)
- 1x Basin (`OF_Formicarium_Basin_M.stl`)
- 1x Lid (`OF_Formicarium_Lid_M.stl`)

**Plexiglass:** 97mm × 97mm × 2mm. Can be press-fit or secured with M3 screws.

### Template M

![Template M](img/16.jpg)

A blank insert for custom designs at the M size. See the [Custom Inserts](#custom-inserts) section below.

### Lasius M

![Lasius M](img/18.jpg)

A ready-to-print *Lasius*-style insert at the larger size.

---

## Custom Inserts

Any tunnel layout can be designed for either size. The insert system is built around a two-step process: draw your layout as a black-and-white image, then combine it with the blank template STL in Microsoft 3D Builder.

**What you need:**

- The blank template STL for your size (`CV2_OF_Formicarium_Template_S.stl` or `_M.stl` from `Formicaria/STL/CV2/`)
- The PSD template for your size from `Formicaria/Inserts/` — open this in Photoshop or any image editor that supports layered files
- Microsoft 3D Builder (free, Windows)

**Workflow:**

1. Open the PSD template in your image editor. It is sized and scaled to match the formicarium's interior footprint.
2. Draw your tunnel and chamber layout on the canvas. Use pure **black** for the areas you want carved out (tunnels, chambers, galleries) and leave the rest **white**. The black areas will become the voids the ants live in.
3. Export your design as a PNG or similar flat image.
4. Open Microsoft 3D Builder. Import the blank template STL, then import your image as a relief/texture to combine with it. 3D Builder will extrude your black areas into the template as cavities.
5. Export the combined result as an STL.

If you create a new species-specific insert and want to share it, see [How to Contribute](contrib.md) for how to submit it to the project.

## Other Sizes

Additional sizes are planned for future releases.
