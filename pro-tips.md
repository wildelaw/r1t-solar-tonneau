---
layout: page
title: "Pro Hints & Watch-Outs"
nav_order: 8
---

# Pro Hints & Things to Watch Out For

## Pro hints

- **Slow hardener is mandatory.** Pouring ~1 gallon of epoxy into a tight space creates a massive exothermic reaction. If you use fast hardener, the resin will boil, turn milky white, and ruin the panel.
- **Batch pouring.** Do not mix more than 32 oz at once, or the bucket will overheat and kick off early. On this build the flood coat was poured **16 oz at a time**, which kept the exotherm manageable and gave time to pour each batch before the previous one gelled.
- **Drill bit sizing.** Make the drill holes for the bus bars slightly oversized. Flat bus wires have sharp corners that can chafe against the fiberglass during thermal expansion. A slightly larger hole prevents this.
- **Size for the loosest channel.** The R1T bed channel width is not consistent — it can measure anywhere from 54 15/16" to 55" along its length. A panel built at the wide end of that range will bind where the channel narrows. For any future or replacement panels, build to **54 3/4" × 13 1/2" × 1/2"** to guarantee clearance across the full channel. The current build stays at **54 7/8" × 13 1/2" × 1/2"** (ground down from 54 15/16" to fix a ~1/16" narrowing at the back of the channel); any specialized or replacement panels will use the new 54 3/4" dimension.
- **Flattened solder ribbon.** Soldering tin strips to the backs of solar cells goes much faster and cleaner if you flatten round solder wire into a thin ribbon and lay it between the cell contact and the tin strip before heating. Apply a soldering flux pen to the contact first — the flux breaks the oxide layer and lets the solder wet evenly. Round solder wire fed by hand is slow and tends to bead up; flattened ribbon gives a uniform bond.
- **Warm resin parts in a hot-water bath before mixing.** This lowers the viscosity, improves flow and wet-out, and makes mixing cleaner.
- **Order cell spares — plan for at least 18 cells per panel.** Two cells broke during back-side soldering on the first panel (16 needed, 18 used). Ordering spares up front avoids a mid-build reorder.
- **Do not lift soldered cells to chase bubbles during the seal coat.** Cells are fragile once strung into a string; assume the seal coat wets them out and that residual air rises out during the flood coat.
- **Heat-gun technique: keep it moving and hold it back.** You want to break the surface tension of the resin, not cook it — or the cells and bus wires underneath.
- **Check bus-wire polarity against the junction box before finalizing cell layout.** Cell alignment can put the positive and negative wires in the opposite positions to the junction box terminals; confirming polarity early avoids having to jury-rig a crossover (e.g. with shrink-tube) after the fact.
- **Test the panel in the sun before pouring the flood coat.** Once the cells are encapsulated in resin they are locked in forever — measuring open-circuit voltage and short-circuit current while the cells are still accessible gives you a chance to replace a bad or cracked cell before it is sealed in.

## Things to watch out for

1. **Amine blush.** If you skip washing the cured fiberglass back skin with soap and water before pouring the flood coat, the invisible waxy blush will act as a release agent. The flood coat will peel off the back skin later.
2. **Sulfur in clay.** Double-check the packaging on your modeling clay. Sulfurized clay (often used for standard sculpting) will emit gases that stop epoxy from curing for a 2-inch radius around the hole, causing a permanent leak.
3. **Steel short circuits.** Ensure no tabbing wire or cell edges are resting directly against bare steel before you pour. Kapton-tape the cross-beams (and the inside bottom edge of the frame if your cells come close to it — on this build they did not, so the frame edges were left untaped since they are already lined with fiberglass).
4. **Resin shrinking.** Epoxy shrinks by about 1-2% as it cures. Pouring slightly *under* the steel frame lip (the 1/16" gap) accounts for this shrinkage perfectly and prevents the panel from looking under-filled.
5. **Resin bonds to scuffed melamine during demold.** Demolding took significant prying and left a warp where the resin had keyed into scuff marks on the board. A silicone release spray was considered but rejected — too much risk of contaminating the steel frame and breaking the resin-to-frame chemical bond. Accept the occasional scuff and shim the edges slowly.
6. **Frame corners lifting off the mold.** If a frame edge is not pressed flush against the melamine before sealing, the resin level in that corner comes out lower than the rest of the panel. Press the frame edges flush against the board before sealing so this does not happen.

---

Back to **[Home]({{ site.baseurl }}{% link index.md %})**.

---

## Version history

| Rev | Date | Description |
|---|---|---|
| 1.0 | 2026-08-01 | Initial finalized release. |
| 1.1 | 2026-08-01 | Added 5 pro hints (warm resin bath, cell spares, seal-coat bubble handling, heat-gun technique, polarity check, pre-resin solar test) and 2 watch-outs (melamine demold bonding, frame-corner lift). |

---

*Content licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) — see [LICENSE](https://github.com/wildelaw/r1t-solar-tonneau/blob/main/LICENSE).*