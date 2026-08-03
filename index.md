---
layout: home
title: "Home"
nav_order: 0
---

# Rivian R1T Solar Tonneau Cover

> **Status: Rev 1.1 — Phase 6 in progress** — Phases 1–5 complete (first panel). Panel 2 layup is underway in Phase 6: the mold is reused with 1/8" hardboard inserts to cut resin weight, and the fiberglass back skin has been wet out with 24 oz of resin. Panels 3–4 and final four-panel wiring still to come.

An engineering & build log for a custom **55" × 13½" × ½" steel-framed solar panel** that replaces the tonneau cover on a Rivian R1T. The panel charges a battery backup power supply stored in the truck bed, or directly powers a cooler in the bed.

## Backstory — why not just buy a cover?

Before this project I built a three-panel tonneau cover out of **3/8" plywood, waterproof canvas, and aluminum C-channel**. It still keeps the bed dry — the canvas is waterproof, though it has faded from its original black — and ½" iron L-beams run underneath to keep the panels from sagging.

{% include figure.html image="/Images/0.1-Old-three-panel-cover.jpeg" caption="The original three-panel plywood + canvas + aluminum C-channel tonneau cover." %}

It works, but it has two problems. The ½" L-beams make the whole assembly heavy and eat into bed storage height, and the cover is a cover — it doesn't do anything but cover.

I could have just done a fiberglass wrap around the new four-panel steel-frame design and called it done. But I had to challenge myself with a more complex project — so I'm encapsulating solar cells in marine epoxy and turning the tonneau cover into a power source. It's also half the estimated cost of buying a manual tonneau cover (currently ~$1000) and, honestly, building it yourself is more fun. The figure below is the new four-panel steel frame test-fit in the same bed channel, for comparison.

{% include figure.html image="/Images/0.2-Bed-full-25-Done.jpeg" caption="Progress so far — one completed solar panel tonneau cover installed in the bed, with three more panel frames to go." %}

---

## Project goals

- **Drop-in fit** on the R1T bed channel — sized to 54⅞" to slide into existing tonneau cover channel.
- **Zero-sag structure** via a welded steel frame with three internal cross-beams.
- **Weatherproof encapsulation** of solar cells in UV-stabilized marine epoxy using the *Direct Bond + Expansion Cap* method.
- **Field-serviceable wiring** through a sealed IP67 junction box on the back skin.
- **Bed-grade output** to feed a portable battery bank or 12V cooler.
- **Low-cost** — keep costs as low as possible, and cheaper than buying a manual tonneau cover (currently $1000!!!)

## Design specs

| Parameter | Value |
|---|---|
| Panel envelope | 55" × 13½" × ½" |
| Frame | Steel L-beam, 54⅞" × ½" × ½" |
| Cross-beams | 3× flat steel, 13" × ⅛", welded at 7", 27½", 48" |
| Back skin | 6oz woven fiberglass, 13¼" × 55" |
| Encapsulant | UV-stabilized clear marine epoxy, slow hardener (~1.13 gal) |
| Top seal | Marine silicone expansion cap, 1/16" gap |
| Wire exits | Two drilled bus-bar pass-throughs, clay-sealed during pour |
| J-Box | Direct-solder IP67, mounted 2" from frame on back skin |

## Build phases

1. ✅ **[Phase 1 — Frame Prep & Bonding Surface]({{ site.baseurl }}{% link build/phase-1-frame-prep.md %})** — *Complete.* Weld, flatten, prime, test-fit in the bed.
2. ✅ **[Phase 2 — Bottom-Up Layup & Hole Drilling]({{ site.baseurl }}{% link build/phase-2-layup.md %})** — *Complete.* Fiberglass back skin, amine blush removal, drill wire exits.
3. ✅ **[Phase 3 — Cell Placement & Routing]({{ site.baseurl }}{% link build/phase-3-cells.md %})** — *Complete.* Kapton insulation, cell stringing, tin-strip soldering, bus-bar routing, clay seal.
4. ✅ **[Phase 4 — The Resin Pour (Direct Bond Method)]({{ site.baseurl }}{% link build/phase-4-resin.md %})** — *Complete.* Seal coat, flood coat, 1/16" expansion gap, heat-gun bubbles, 48-hour cure.
5. ✅ **[Phase 5 — Post-Cure, Expansion Cap & J-Box Soldering]({{ site.baseurl }}{% link build/phase-5-post-cure.md %})** — *Complete.* Demold, putty removal, expansion cap (skipped on first panel), J-Box wired + tested (9.6 V open, 6.76 A short-circuit, ~54 W), test fit in the truck bed.
6. 🛠️ **[Phase 6 — Do It Three More Times]({{ site.baseurl }}{% link build/phase-6-more-panels.md %})** — *In progress.* One panel doesn't quite cover the whole bed — the truck bed needs four. All four frames were welded together during Phase 1, so no new Phase 1 work is needed. Panel 2 is in its Phase 2 layup: the mold is reused with 1/8" hardboard inserts to bring the fiberglass bottom level with the cross bars (reducing resin weight in the center), and the fiberglass back skin is wet out with 24 oz of resin. Then solder ~54 more tin strips (plus the inevitable breakage), pour more resin, demold, wire the J-Boxes, and finally wire all four panels together and go camping.

## Reference

- **[Materials list]({{ site.baseurl }}{% link materials.md %})** — full bill of materials with resin volume math.
- **[Pro hints & watch-outs]({{ site.baseurl }}{% link pro-tips.md %})** — failure modes and hard-won lessons.
- **[Original directions](https://github.com/wildelaw/r1t-solar-tonneau/blob/main/Docs/Directions.md)** — canonical source document in `Docs/Directions.md`.

## Outcome so far

Phase 1 is complete. The steel frame is welded, flattened, primed, and test-fit in the R1T bed. Final bed fit is verified — the panel sits flush in the bed channel with a clean gap at the tailgate end, ready for the resin pour and cell stringing phases. The frame was ground down from 54 15/16" to 54 7/8" to correct a ~1/16" narrowing at the back of the channel and now drops in cleanly.

Phase 2 is complete. The fiberglass back skin is laid up, amine blush removed, and the dark grey epoxy paint applied. Wire-exit holes were drilled (aligned for the positive and negative bus wires) and sealed with plumber's putty ready for the pour.

Phase 3 is complete. The cross-beams were Kapton-taped (the frame edges did not need it), and all 16 cells had tin strips soldered to their backs — a slow process, eased by flattened solder ribbon and a flux pen. Two cells broke during soldering and had to be replaced (18 total). The positive and negative bus bars are soldered to the strings, routed through the back-skin holes, and sealed with plumber's putty and a Kapton-tape cover.

Phase 4 is complete. The back skin was re-scuffed with 120-grit and acetone-wiped, the mold was leveled, and a seal coat was skimmed over all the cells. After a ~3-hour gel, the flood coat was poured 16 oz at a time up to just below the top of the frame (leaving the 1/16" expansion gap), bubbles were cleared with a heat gun, and the panel cured level for 48 hours.

Phase 5 is complete (Rev 1.0). The panel was demolded — it took more effort than expected, slowly shimming the edges free where the resin had bonded to scuffed spots on the melamine, and the prying torque left a warp in the panel. The plumber's putty was peeled out of the wire-exit holes cleanly. The expansion cap was skipped for the first panel (the L-beam frame does not need it the way the original C-rail design did). The J-Box is now wired: red shrink-tube crosses the + and − bus wires over to match the junction box polarity, the box is bonded with white construction adhesive, and the leads are final-soldered. The panels will use standard MC4 connectors with an adapter to the Anderson connector on the Harbor Freight Predator power bank. Before snapping on the cover, the panel was tested in the sun: 9.6 V open-circuit and 6.76 A short-circuit (~54 W), down from the 6.96 A (≈66 W) measured before resin-enclosing — two cells cracked during demolding and the resin likely blocks some light. The completed panel plus the three remaining frames were test-fit in the truck bed and everything clears; the completed frame sags ~1/8" in the center, and the next panel needs to be lighter. The first panel is finished — the truck bed needs four.

{% include figure.html image="/Images/5.5-First-panel-complete.jpeg" caption="First panel complete (minus the junction box) — a steel L-beam will be added across the bottom for support, and hopefully the next one will be lighter." %}

Phase 6 is in progress (Rev 1.1). All four steel frames were welded at the same time during Phase 1, so no new frame work is needed for panels 2–4. Panel 2 is in its Phase 2 layup: the mold from Panel 1 is being reused, with four 1/8" hardboard inserts attached to bring the fiberglass bottom level with the cross bars — this reduces the resin volume pooled in the center of the panel, addressing the weight problem from the first panel. The hardboard pieces are white-on-one-side / black-on-the-other and attached to the mold surface; if the panel demolds cleanly and the inserts release intact, they will be reused for panels 3 and 4. The fiberglass back skin has been wet out with 24 oz of resin (vs. 16 oz on Panel 1, the extra to seal around the hardboard and the deeper cross-bar pockets). The hardboard is hygroscopic — it absorbs moisture from the air and moves with humidity at a different rate than the cured resin — but it sits on the back-skin side of the cross-bars, well clear of the solar cells, so any dimensional change should not stress the cells; once encased in resin the moisture exchange is largely cut off and it stabilizes. Next: cure 24 hours, amine-blush removal + back-skin paint, then drill the wire exits in Phase 2 (the deferred-drilling lesson from Panel 1) before moving on to cell soldering.

---

*Upcoming sections will cover electrical configuration, battery integration, cooler wiring, and field test results as the build progresses.*

---

## Version history

| Rev | Date | Description |
|---|---|---|
| 1.0 | 2026-08-01 | Initial finalized release. |
| 1.1 | 2026-08-02 | Phase 6 started: Panel 2 layup underway (mold reused with 1/8\" hardboard inserts to cut resin weight, fiberglass wet out with 24 oz of resin). Added Phase 6 page and outcome paragraph; updated status line and phase list item 6. |
| 1.2 | 2026-08-02 | Corrected hardboard watch-out (hygroscopic moisture movement, not resin absorption) in the Phase 6 outcome paragraph. |

---

*Content licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) — see [LICENSE](https://github.com/wildelaw/r1t-solar-tonneau/blob/main/LICENSE).*