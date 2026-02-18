# Tips & References

This is a supplementary reference document compiled from ant keeping communities, 3D printing guides, and related open-source projects. It covers topics in more depth than the main docs — useful once you have your first setup running and want to go further.

---

## Other Notable Open-Source / Free 3D Printed Ant Formicarium Projects

### Modular Expandable Ant Formicarium by TeachingTech
- **Printables:** https://www.printables.com/model/180141-modular-expandable-ant-formicarium
- Modular design with expandable sections
- Well-documented build with community remixes
- Worth reviewing for design ideas (e.g. ventilation, connector approaches)

### Medium Modular Formicarium (Ant Farm) — Instructables
- **Instructables:** https://www.instructables.com/Medium-Modular-Formicarium-Ant-Farm/
- 18-step build guide with pictures
- Covers materials, assembly, and humidity management in detail

### Automated Formicarium — Hackaday.io
- **Hackaday:** https://hackaday.io/project/169904-automated-formicarium-ant-farm
- Electronic temperature and humidity automation
- Could inspire a future "advanced setup" doc section

---

## Anti-Escape: Fluon (PTFE) Application

Source: Ant forum community discussions (formiculture.com, tapatalk antfarm forum)

### Safety Warning
- **Wet Fluon is toxic to ants.** Always allow it to dry completely before ants can access treated surfaces. Drying takes approximately 10 minutes for diluted versions; allow longer for full-strength applications.

### Application Tips
- **Dilution:** Mix at a 1:5 ratio (Fluon to water). Results in a nearly transparent coating. Effectiveness is slightly reduced compared to full-strength, but coverage is easier to verify by going over it again.
- **Coats:** Apply 3–8 layers for reliable results. A single coat — even at full strength — is often insufficient; determined ants can cross it.
- **Timing:** Apply when the colony is naturally dormant (evening for some species, midday when well-fed for others). This minimises the risk of ants contacting wet Fluon.
- **Containment during application:** Drop a small pill container over any wandering ants until the Fluon dries. Alternatively, temporarily move the outworld and swap in a pre-treated replacement once dry.
- **Storage:** Shake the bottle regularly — Fluon settles during storage and loses effectiveness if not mixed.

### Limitations
- Removing old Fluon residue from an active colony enclosure is very difficult without fully relocating the colony. Plan application carefully before introducing ants.

### Alternative Barrier: Petroleum Jelly (Vaseline)
- A common alternative to Fluon — smear a band around the inner wall of the outworld or enclosure.
- Less durable and needs reapplication more frequently, but safer and easier to source.
- Does not work well on rough or porous surfaces (3D printed PLA without post-processing tends to need multiple coats or sanding first).

---

## Heating

Sources: formiculture.com, ant-shack.com, forum.antscanada.com

### Methods

| Method | Notes |
| --- | --- |
| **Heating cable** | Generally preferred. Can be woven around or beneath one side of the nest. Allows a temperature gradient. |
| **Heating mat / heat pad** | Surface temperature typically 30–40°C. Place under one side only — not the whole nest — so ants can thermoregulate. |
| **Ceramic heater** | Less common for small setups. |
| **Heat lamp (red/infrared)** | Used by some keepers for ambient warmth. Keep distance to avoid drying out the nest. |

### Temperature Ranges

| Colony type | Target temperature |
| --- | --- |
| Most temperate species (Lasius, Formica, Camponotus) | 22–26°C |
| Tropical species (Atta, Oecophylla, etc.) | 26–30°C (75–86°F) |
| Hibernating species (winter diapause) | 4–10°C — do not heat during this period |

### Key Principles
- **Always heat only one side** of the nest — never the whole enclosure. This creates a thermal gradient so ants can move between warm brood-rearing areas and cooler foraging zones.
- **Use a thermostat.** Even inexpensive digital thermostats with a probe sensor prevent dangerous overheating. Overheating kills colonies quickly.
- **Do not heat the outworld.** Ants regulate their own behaviour based on nest temperature; the foraging area does not need supplemental heat.
- The OpenFormicaria formicarium basin includes a heat cable channel — route the cable through this channel, keeping the cable confined to one side of the nest for a proper gradient.

---

## Humidity and Hydration in 3D Printed Nests

Sources: formiculture.com, antnook.net, poramorart.ca

### The Core Challenge
Plastic does not absorb or wick water the way sand, clay, or gypsum does. This means humidity in a 3D printed nest must be managed deliberately — the material itself provides no passive buffer.

### Practical Approaches

**Water basin / reservoir (built-in)**
The OpenFormicaria formicarium basin includes a water reservoir. Fill this with water and allow slow evaporation to humidify the nest. Top up regularly (frequency depends on ambient humidity and nest size).

**Internal water feeder**
A small bottle or container (5ml–10ml glass vials work well) placed inside the outworld or at a feeding port provides a direct drinking source. Worker ants carry water back to the nest in their crop to distribute moisture to brood and nestmates.

**Cotton / sponge inserts**
Some keepers fill the water reservoir or a dedicated side chamber with a cotton ball or mold-resistant sponge to slow evaporation and provide a sustained moisture source.

**Misting**
Light misting of the nest exterior (not interior) can raise humidity short-term. This is more effective in enclosed systems. Avoid over-misting plastic nests — condensation pooling in chambers can drown brood.

### Signs of Humidity Problems
- **Too dry:** Brood desiccates, queen lays fewer eggs, workers appear lethargic.
- **Too wet:** Mold appears in chambers. If mold reaches dangerous levels, ants will naturally try to relocate.

---

## Test Tube to Formicarium Transition

Sources: forum.antscanada.com, ant keeping community guides

### When to Transition
- When the colony has outgrown the test tube — crowding is visible, or the queen has 15–30+ workers.
- When mold is building up in the test tube and can't easily be addressed.
- Generally, a founding colony takes approximately one year to reach 100+ workers from a single founding queen.

### How to Do It

**Let ants move themselves (strongly recommended)**
Connect the test tube directly to the formicarium entrance. Cover the formicarium to make it dark and appealing. The colony will usually relocate on their own over 1–7 days. Do not force the process.

**Light trick**
Shine a bright light into the test tube while keeping the formicarium covered and dark. The contrast encourages ants to move toward the dark nest. This works particularly well for species that strongly prefer darkness.

**Patience approach**
Place the test tube inside the outworld or a larger container temporarily. Ants explore and relocate at their own pace.

### Key Precautions
- Never disturb the queen during transfer — stress can halt egg-laying for days or weeks.
- Remove the test tube only after the colony has fully established in the new nest (all brood moved, queen settled).
- If using the Portal module: the tube connector system is designed exactly for this — connect the test tube to the Portal's tube port and let the colony move naturally.

---

## Filament Guidance

### PLA vs PETG for Modules

| Property | PLA | PETG |
| --- | --- | --- |
| Ease of printing | Very easy | Moderate |
| Heat resistance | Low (~60°C) | Better (~80°C) |
| Ant safety | Generally safe when fully cured | Generally safe |
| Post-processing | Sands/paints easily | Slightly harder to sand |
| Long-term durability | Can become brittle over years | More flexible, more durable |
| Recommendation | Fine for most setups | Preferred if using heat cable |

> Note: If using a heat cable inside the formicarium basin, PETG is the safer choice for the formicarium itself, as PLA can warp if the cable runs hot. For modules without heating, PLA is perfectly adequate.

### TPU Print Settings (for connectors)

Sources: MatterHackers, Ultimaker, 3D Printerly, Siraya Tech

| Setting | Recommended value |
| --- | --- |
| Nozzle temperature | 220–240°C (varies by brand — check datasheet) |
| Bed temperature | 40–60°C |
| Print speed | 20–30 mm/s (slow is key) |
| Retraction distance | 1–2mm or disabled |
| Retraction speed | 10–20 mm/s |
| Extruder type | Direct drive strongly preferred — Bowden extruders struggle with TPU |

**Moisture:** TPU absorbs moisture from air (hygroscopic). Dry your spool before printing if it has been stored open, or if you see popping/bubbling during extrusion. Store in an airtight container with desiccant.

**Key tip:** Printing too fast is the most common cause of poor TPU results. If connectors are stringy or underextruded, reduce speed to 20mm/s or below before changing anything else.

---

## Acrylic / Plexiglass Sourcing

Sources: formiculture.com, ant forum discussions

### Where to Buy Cut-to-Size Acrylic
- **Local hardware stores** (Home Depot, B&Q, etc.) — usually carry 2–3mm acrylic sheet, can be cut at home with a scoring tool or jigsaw.
- **Online laser cutting services** (Ponoko, Send Cut Send, etc.) — upload a DXF with the exact panel dimensions and receive precision-cut pieces. Cost-effective for multiple panels.
- **Hobby stores** (Michaels, Hobby Lobby) — carry small acrylic and glass frames that may be close to required sizes.
- **eBay / Amazon** — acrylic sheet sold by the piece in standard sizes; requires home cutting.

### Material Notes
- **Standard recommendation: 2mm acrylic sheet.** Thinner (1mm) can crack during press-fitting. Thicker (3mm) won't fit the 3mm-deep glass cutout in OpenFormicaria modules.
- Acrylic scratches more easily than glass and can become cloudy over time with humidity exposure. Use a soft cloth for cleaning.
- **Real glass** (cut by a glazier) is more scratch-resistant and stays clearer long-term, but is heavier and more fragile to cut precisely. Some keepers prefer glass for the viewing panel on formicaria.
- Plexiglass/acrylic can warp slightly over time in high-humidity environments — this is rarely a problem at 2mm thickness in a module-sized panel.

---

## Community Tips and Observations

From Printables and forum discussions:

- **Colour selection matters more than most people expect.** Black or very dark modules make it almost impossible to see light-coloured species (Lasius, Formica) without strong side-lighting. White or light grey is generally easiest for observation.
- **Print the separator in pairs** — the design requires two to properly block a connection from both sides simultaneously.
- **Feeder lids in TPU:** The Portal feeder lids must be TPU or they will not press-fit properly. PLA lids will either not seat or crack on insertion.
- **The Connector Raiser** is easy to overlook but important — without it, a Portal sitting at module height will float above a formicarium that sits higher due to its basin. Print at least one per formicarium connection point.
- Some keepers print the formicarium lid and basin in opaque black to give ants a dark environment and then use the clear plexiglass only for the insert viewing window.

---

## Gaps in Current OpenFormicaria Documentation (Suggested Additions)

Based on community research, the following topics are frequently asked about but not currently covered:

1. **Anti-escape coating guide** — Fluon PTFE and petroleum jelly application, with safety warnings
2. **Heating setup guide** — how to route the heat cable, thermostat recommendation, temperature targets by species
3. **Humidity management** — how to use the water basin, internal feeder options, recognising humidity problems
4. **Test tube transition guide** — step-by-step with timing advice
5. **Filament selection notes** — when to use PETG instead of PLA (heat cable setups), TPU printing tips
6. **Acrylic sourcing guide** — where to get it cut to size, material tradeoffs vs real glass
7. **Colony size / upgrade guide** — when to move from Portal → Size S → Size M formicarium

---

## Sources Referenced

- https://www.printables.com/model/180141-modular-expandable-ant-formicarium
- https://www.instructables.com/Medium-Modular-Formicarium-Ant-Farm/
- https://hackaday.io/project/169904-automated-formicarium-ant-farm
- https://www.formiculture.com/topic/16127-3d-printed-nest-hydration/
- https://www.formiculture.com/topic/2697-any-ideas-for-heating-a-formicarium/
- https://www.formiculture.com/topic/15031-glass-acrylic-panes-for-diy-formicarium/
- https://www.tapatalk.com/groups/antfarm/fluon-ptfe-question-t17152.html
- https://www.ant-shack.com/blogs/ant-articles/ant-colony-temperature-regulation-ensuring-optimal-conditions
- https://www.forum.antscanada.com/viewtopic.php?t=2790
- https://antnook.net/products/3d-printed-internal-water-feeder-for-ant-nest-5ml-10ml-glass-bottle-for-hydration-humidity-control
- https://www.poramorart.ca/hybrid-formicaria-guide
- https://www.matterhackers.com/articles/how-to-succeed-when-printing-with-flexible-filament
- https://ultimaker.com/learn/printing-with-tpu-best-practices-for-flexible-success/
- https://3dprinterly.com/filament-printing-guide/tpu/
