# Connectors

Connectors are the **linking pieces** between modules and formicaria. Every module face has a built-in female port — connectors are the standalone pieces you insert into those ports to join two faces together, block a passage, or attach tubing. Without a connector in a port, the port is just an open hole.

All connectors must be printed in **TPU or a similar flexible material**. TPU compresses slightly when fitted, forming a tighter seal than rigid materials — this matters for ant containment.

> **Escape prevention tip:** For species with workers under 3mm, apply a thin bead of aquarium-safe silicone along the inner edge of each plexiglass channel before seating the panel. This closes micro-gaps caused by print surface texture or slight warping.

## Print Settings

- 0.2mm layer height
- 15% infill
- Tube connectors require supports; everything else prints without supports

## CV2 Connector Standard

All connectors follow the CV2 design: a Hill/Rail/Groove locking mechanism. The female port on each module face has a central Hill; the male connector has a matching Rail and Groove that slides over the Hill and locks. The connector is inserted from the front and clicks into place.

The key benefit of this system is that **connectors can be swapped while the setup is occupied**. You never need to open an unsealed gap — slide a Separator in first to block both sides, swap the connector behind it, then remove the Separator. No ant can escape during the process.

---

## Main Connector

![Main Connector](img/3.jpg)

**File:** `V2_Connector.stl`

The standard pass-through connector. Bridges two module ports face-to-face, opening a passage between them. You need one per active connection in your layout — if two modules are touching, there is a Main Connector between their facing ports.

## Connector Blocker

![Connector Blocker](img/4.jpg)

**File:** `V2_Connector_Blocker.stl`

Identical in shape to the Main Connector but solid — no passage through it. Blocks the port on one side only. Use it to close off a port you don't plan to use, or to permanently seal a connection point.

> **Blocker vs Blocking Endpoint:** The Blocker fits into a port on one module; the Blocking Endpoint caps a port from the outside as a finished dead-end. Use the Blocker when you want to seal a port mid-layout; use the Blocking Endpoint for any port that is simply unused and facing outward.

## Tube Connectors (10mm, 12mm, 14mm)

![Tube Connectors](img/5.jpg)

**Files:** `V2_Connector_tube10mm.stl`, `V2_Connector_tube12mm.stl`, `V2_Connector_tube14mm.stl`

Connects a module port to vinyl or glass tubing. The three sizes refer to the **inner diameter of the tubing** — choose the size that matches your test tubes or tubing. The tube slides **over** the connector nub, not inside it; push until it seats firmly.

Use tube connectors to route a passage between modules that aren't placed side-by-side, or to attach a test tube directly to the setup when transferring a founding colony.

## Tube Connectors 90° (10mm, 12mm, 14mm)

![Tube Connectors 90°](img/6.jpg)

**Files:** `V2_Connector_90deg_tube10mm.stl`, `V2_Connector_90deg_tube12mm.stl`, `V2_Connector_90deg_tube14mm.stl`

Same as the straight tube connector but the tubing exits at a right angle to the module face. Useful when space is tight or you need to run tubing along a wall or shelf edge rather than straight out from the front.

## Blocking Endpoint

![Blocking Endpoint](img/7.jpg)

**File:** `V2_Blocker_Endpoint.stl`

A flush cap for any port that is simply unused. Cleaner-looking than a Blocker in an exposed position, and clearly signals that this port is a dead end. Unlike the Main Connector and Blocker, it covers only one side — it cannot bridge two modules. Print several extras; any setup will have a number of outward-facing unused ports.

## Connector Raiser

![Connector Raiser](img/8.jpg)

**File:** `V2_Connector_Raiser.stl`

A stepped connector that bridges the height difference between a Portal and a formicarium. Because the formicarium sits on a water basin, it stands slightly taller than a Portal placed on the same surface. Without a Raiser, a direct side-by-side connection between the two would leave the Portal floating. Use one Raiser per connection point where a flat module meets a formicarium.

## Separator

![Separator](img/9.jpg)

**File:** `V2_Seperator.stl`

Blocks both sides of a connection point simultaneously by sliding in from above, between two joined module faces. Unlike a Blocker (which you swap in for an existing connector), the Separator does not replace the connector — it adds a physical barrier on top of it, sealing both sides at once with no gap ever opening.

Use a Separator any time you need to divide your setup: isolating a sick colony, closing off a section for cleaning, or safely separating modules for transport. Print at least two — you will use them in pairs to isolate a section from both ends.
