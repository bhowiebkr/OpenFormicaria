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

A blank insert — no ant pathways. Use this as the base for creating your own custom insert design. See [How to Contribute](contrib.md) for the Photoshop + 3D Builder workflow.

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

A blank insert for custom designs at the M size. See [How to Contribute](contrib.md) for the workflow.

### Lasius M

![Lasius M](img/18.jpg)

A ready-to-print *Lasius*-style insert at the larger size.

---

## Custom Inserts

Any insert style can be created for any size template. The workflow:

1. Open the PSD template from `Formicaria/Inserts/` in Photoshop (or any compatible editor)
2. Draw your tunnel and chamber layout in black and white — black areas become the ant tunnels
3. Import the result into Microsoft 3D Builder alongside the blank template STL and combine them
4. Export the combined mesh as an STL

The blank template STLs and PSD files are included in the repository so anyone can create species-specific layouts.

## Other Sizes

Additional sizes are planned for future releases.
