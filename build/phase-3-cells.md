---
layout: page
title: "Phase 3 — Cell Placement & Routing"
nav_order: 4
---

# Phase 3: Cell Placement & Routing

> **Status: Complete.** Steps were revised as the work progressed. Soldering tin strips to the backs of the cells was by far the longest part of the build — 18 cells had to be soldered (two broke during the process and had to be replaced).

## 1. Insulate the Cross-Beams

Solar cells cannot touch bare steel or they will short out and crack under flex. Kapton-tape the *metal cross-beams* only — the frame edges did not need taping because the cells do not come close to the edges and the edges are already lined with fiberglass.

## 2. Set Up a Soldering Board

Use a separate melamine board the same length as the panel as a soldering work surface. Lay the cells face-down on it and work along the row, soldering the tin strips to the back contacts of each cell.

{% include figure.html image="/Images/3.1-First-soldered-cell.jpeg" caption="The first cell with its tin strip soldered to the back contacts." %}

## 3. Solder the Tin Strips

Solder a tin strip to the back of every cell. This is a long, slow process — 16 cells in the panel, and **observation:** two broke during soldering and had to be replaced (18 total). **Update for next panel:** Plan for spares — order at least 18 cells per panel to cover breakage.

**Observation:** The first cell was rough, but quality improved significantly after switching to **flattened solder** — take a length of solder wire and flatten it into a thin ribbon with a mallet or rolling surface, then lay a strip of it between the cell contact and the tin strip before applying heat. The flattened solder gives a far more even bond than trying to feed round solder wire in by hand.

{% include figure.html image="/Images/3.2-Flattened-solder.jpeg" caption="Flattened solder ribbon laid between the cell contact and the tin strip before soldering." %}

Also apply a **soldering flux pen** to the contact area before laying down the flattened solder and the tin strip. The flux cleans the oxide off the contact and lets the solder wet out evenly.

{% include figure.html image="/Images/3.3-Soldering-flux-pen.jpeg" caption="Soldering flux pen applied to the back contact before laying down the flattened solder." %}

## 4. Route the Bus Bars

After all cells are soldered and strung together, solder the main positive and negative flat bus bars to the cell strings. Leave the ends of the bus bars about 4 inches too long and push the excess down *through* the two drilled holes in the back skin so they stick out the bottom of the panel.

## 5. Seal the Holes (Clay + Kapton)

From the *inside* (top) of the panel, pack non-sulfur modeling clay (plumber's putty works) tightly around the bus wires where they pass through the fiberglass. Build a solid 1-inch mound. *Do not use standard sulfur-based clay, as sulfur inhibits epoxy curing.*

**Observation:** I also laid a strip of Kapton tape over the clay and the bus bars on top. It may not actually help seal the holes, but it made me feel better about keeping the putty in place and the holes sealed during the pour. **Update for next panel:** Pending — will confirm whether the Kapton strip actually improves the seal and convert to a pro-tip if it does.

{% include figure.html image="/Images/3.4-Bus-bars-plumbers-putty.jpeg" caption="Bus bars routed through the drilled holes and sealed with plumber's putty, then taped over with Kapton." %}

---

Previous: **[Phase 2 — Bottom-Up Layup & Hole Drilling]({{ site.baseurl }}{% link build/phase-2-layup.md %})**
Next: **[Phase 4 — The Resin Pour]({{ site.baseurl }}{% link build/phase-4-resin.md %})**

---

*Content licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) — see [LICENSE](https://github.com/wildelaw/r1t-solar-tonneau/blob/main/LICENSE).*