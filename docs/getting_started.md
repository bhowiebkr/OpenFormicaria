# Getting Started

## Download

Download the STL files from [Printables](https://www.printables.com/model/45114-openformicaria-a-modular-ant-housing-platform), [Thingiverse](https://www.thingiverse.com/thing:4637707), or directly from [GitHub](https://github.com/schemen/OpenFormicaria) for the latest versions. Files are in the `STL` folders within each category.

## Choosing Your Ants

OpenFormicaria works best with ant species whose workers are **3mm or larger**. Very small ants (under 2mm) can slip through micro-gaps at the plexiglass panel edge and are not recommended without additional sealing.

For beginners, **Lasius niger** (black garden ant) is the most commonly recommended species — workers are 3–5mm, they are hardy, widely available in Europe, and their shallow disc-shaped nesting style suits the module format well. **Camponotus** (carpenter ants) are another great choice: large workers eliminate escape risk entirely.

See the [Ant Species Guide](ant_species.md) for a full compatibility table and care requirements.

## Required Materials

- **Hard filament** (PLA, PETG, or similar) — for all modules and formicaria
- **Flexible filament** (TPU, Flex, or similar) — required for all connectors; also recommended for Portal feeder lids

## Print Settings

### Modules and Formicaria (hard filament — PLA, PETG, or similar)

| Setting | Value |
| --- | --- |
| Layer height | 0.2mm |
| Infill | 15% |
| Walls (perimeters) | 3 |
| Supports | Not required |
| Material | PLA, PETG, or any rigid filament |

> **Tip:** Print modules in a colour that contrasts with your ants — light grey or white works well for most species. Avoid very dark colours if your ants are light-coloured (Lasius, Formica), as they become nearly impossible to spot without strong side-lighting.
>
> **Formicaria note:** If you are using a heat cable inside the basin, PETG is the safer choice — PLA can warp if the cable runs hot. For modules without heating, PLA is fine.

### Connectors (flexible filament — TPU or similar)

| Setting | Value |
| --- | --- |
| Layer height | 0.2mm |
| Infill | 15% |
| Walls (perimeters) | 3 |
| Supports | Required for tube connectors only; not needed for others |
| Material | TPU or other flexible filament — **do not substitute rigid filament** |

TPU compresses slightly when fitted into a port, forming a tight seal. Rigid filament connectors will not seal properly and create escape gaps.

**TPU print tips:**

- Print slowly — 20–30mm/s. Speed is the most common cause of TPU failure. If you see stringing or underextrusion, reduce speed before changing anything else.
- Direct drive extruder is strongly preferred. Bowden setups can work but require very dialled-in retraction settings (1–2mm, 10–20mm/s, or disabled).
- If your filament has been stored open, dry it before printing — TPU is hygroscopic and absorbs moisture, which causes popping and poor layer adhesion.

See [Tips & References](research_notes.md) for a full TPU settings table.

## Parts Overview

OpenFormicaria has three categories of parts. Each links to a dedicated page with print settings and part descriptions:

- [Connectors](connectors.md) — must be printed in TPU; connect, block, and seal passages between modules
- [Modules](modules.md) — Portal and Gateway outworld/expansion pieces
- [Formicaria](formicaria.md) — the nest chambers in Size S and Size M

All connectors use the CV2 Hill/Rail/Groove locking mechanism, which lets you swap connectors while the setup is occupied — no risk of ants escaping during changes.

![Connectors](img/2.jpg)

## Starter Builds

### The Base Kit

![Basekit](img/13.jpg)

The Portal is the natural starting point. It gives a small colony a space to explore while still living in a test tube, and it connects directly to tubes, outworlds, and formicaria as the colony grows.

**Print list:**

- 1x Portal
  - 2x Portal Feeder Lids (print in TPU)
  - 1x Portal Lid
  - 26mm × 62mm × 2mm plexiglass
- 2x Separators
- 3x Blocking Endpoint
- 2x Tube Connectors (sized to your test tube — the second can connect water or an outworld)

### Adding a Formicarium

![Formicarium](img/14.jpg)

Once the colony needs a proper nest, start with the Size S formicarium. Connect it directly to the Portal or run tubing between them.

**Print list:**

- 1x Size S Formicarium
  - 62mm × 62mm × 2mm plexiglass
- 3x Blocking Endpoint (4x if connecting via tubes)
- 1x Connector Raiser **or** 1x Tube Connector — use the Raiser for a direct side-by-side connection to the Portal, or a Tube Connector if you want to run tubing between them

## Moving Ants from Test Tube to Formicarium

When your colony is ready, **let the ants move themselves** — do not force them. Connect the test tube to the Portal or formicarium entrance using a tube connector, then leave the setup alone. The colony will relocate on their own within a few days.

To encourage faster movement: shine a bright light on the test tube while keeping the formicarium covered and dark. Ants strongly prefer darkness and will move toward it.

Remove the test tube only after all brood and the queen have settled into the new nest. Avoid disturbing the queen during the transition — stress can halt egg-laying for days.
