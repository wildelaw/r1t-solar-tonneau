---
layout: home
title: "Home"
nav_order: 0
---

# Rivian R1T Solar Tonneau Cover

> **Status: Rev 1.10 — Phase 6 in progress** — Phases 1–5 complete (first panel). Panels 1–3 are complete and test-fit in the truck bed; only Panel 4 remains. Panel 2 tested with Panel 1 at 17.34 V / 4.06 A (~70 W) under load; Panel 1 has 5 of 16 cells cracked from a trapped air bubble; Panel 3 has one small center-cracked cell and its bus bars on the opposite holes. Panel 4 is planned as the battery/inverter mount with a locked access panel, optionally ~8 cells covering ~50%. Final four-panel wiring still to come.

An engineering & build log for a custom **55" × 13½" × ½" steel-framed solar panel** that replaces the tonneau cover on a Rivian R1T. The panel charges a battery backup power supply stored in the truck bed, or directly powers a cooler in the bed.

## Backstory — why not just buy a cover?

Before this project I built a three-panel tonneau cover out of **3/8" plywood, waterproof canvas, and aluminum C-channel**. It still keeps the bed dry — the canvas is waterproof, though it has faded from its original black — and ½" iron L-beams run underneath to keep the panels from sagging.

{% include figure.html image="/Images/0.1-Old-three-panel-cover.jpeg" caption="The original three-panel plywood + canvas + aluminum C-channel tonneau cover." %}

It works, but it has two problems. The ½" L-beams make the whole assembly heavy and eat into bed storage height, and the cover is a cover — it doesn't do anything but cover.

I could have just done a fiberglass wrap around the new four-panel steel-frame design and called it done. But I had to challenge myself with a more complex project — so I'm encapsulating solar cells in marine epoxy and turning the tonneau cover into a power source. It's also half the estimated cost of buying a manual tonneau cover (currently ~$1000) and, honestly, building it yourself is more fun. The figure below is the new four-panel steel frame test-fit in the same bed channel, for comparison.

{% include figure.html image="/Images/6.11-Three-panels-test-fit.jpeg" caption="Progress so far — three completed solar panels test-fit in the truck bed; only Panel 4 (the battery/inverter mount panel) remains." %}

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
5. ✅ **[Phase 5 — Post-Cure, Expansion Cap & J-Box Soldering]({{ site.baseurl }}{% link build/phase-5-post-cure.md %})** — *Complete.* Demold, putty removal, expansion cap (skipped on first panel), J-Box wired + tested (9.6 V open, 6.76 A short-circuit, ~65 W), test fit in the truck bed.
6. 🛠️ **[Phase 6 — Do It Three More Times]({{ site.baseurl }}{% link build/phase-6-more-panels.md %})** — *In progress.* One panel doesn't quite cover the whole bed — the truck bed needs four. All four frames were welded together during Phase 1, so no new Phase 1 work is needed. Panel 2 is complete and demolded (the hardboard insert modification reduced its weight, though the inserts stuck to the back because they weren't sprayed with release); Panel 1 and Panel 2 wired together under load (driving an inverter at its minimum supported voltage) deliver 17.34 V at 4.06 A (~70 W) in non-peak sun, and Panel 1 was found to have 5 of 16 cells cracked from a trapped air bubble. After a shop delay (another project needed a long lacquer-blush cure), Panel 3's cells were soldered and the resin poured — the polarity check was skipped again (bus bars on the opposite holes) and one cell cracked (~2 cm × 1 cm, center) while removing air bubbles. Panel 3 is now complete, and all three finished panels are test-fit in the truck bed. Panel 4 will be the battery/inverter mount with a locked access panel, optionally ~8 cells covering ~50% of it. Then wire all four panels together and go camping.

## Reference

- **[Materials list]({{ site.baseurl }}{% link materials.md %})** — full bill of materials with resin volume math.
- **[Pro hints & watch-outs]({{ site.baseurl }}{% link pro-tips.md %})** — failure modes and hard-won lessons.
- **[Original directions](https://github.com/wildelaw/r1t-solar-tonneau/blob/main/Docs/Directions.md)** — canonical source document in `Docs/Directions.md`.

## Outcome so far

Phase 1 is complete. The steel frame is welded, flattened, primed, and test-fit in the R1T bed. Final bed fit is verified — the panel sits flush in the bed channel with a clean gap at the tailgate end, ready for the resin pour and cell stringing phases. The frame was ground down from 54 15/16" to 54 7/8" to correct a ~1/16" narrowing at the back of the channel and now drops in cleanly.

Phase 2 is complete. The fiberglass back skin is laid up, amine blush removed, and the dark grey epoxy paint applied. Wire-exit holes were drilled (aligned for the positive and negative bus wires) and sealed with plumber's putty ready for the pour.

Phase 3 is complete. The cross-beams were Kapton-taped (the frame edges did not need it), and all 16 cells had tin strips soldered to their backs — a slow process, eased by flattened solder ribbon and a flux pen. Two cells broke during soldering and had to be replaced (18 total). The positive and negative bus bars are soldered to the strings, routed through the back-skin holes, and sealed with plumber's putty and a Kapton-tape cover.

Phase 4 is complete. The back skin was re-scuffed with 120-grit and acetone-wiped, the mold was leveled, and a seal coat was skimmed over all the cells. After a ~3-hour gel, the flood coat was poured 16 oz at a time up to just below the top of the frame (leaving the 1/16" expansion gap), bubbles were cleared with a heat gun, and the panel cured level for 48 hours.

Phase 5 is complete (Rev 1.0). The panel was demolded — it took more effort than expected, slowly shimming the edges free where the resin had bonded to scuffed spots on the melamine, and the prying torque left a warp in the panel. The plumber's putty was peeled out of the wire-exit holes cleanly. The expansion cap was skipped for the first panel (the L-beam frame does not need it the way the original C-rail design did). The J-Box is now wired: red shrink-tube crosses the + and − bus wires over to match the junction box polarity, the box is bonded with white construction adhesive, and the leads are final-soldered. The panels will use standard MC4 connectors with an adapter to the Anderson connector on the Harbor Freight Predator power bank. Before snapping on the cover, the panel was tested in the sun: 9.6 V open-circuit and 6.76 A short-circuit (~65 W), down from the 6.96 A (≈67 W) measured before resin-enclosing — two cells cracked during demolding and the resin likely blocks some light. The completed panel plus the three remaining frames were test-fit in the truck bed and everything clears; the completed frame sags ~1/8" in the center, and the next panel needs to be lighter. The first panel is finished — the truck bed needs four.

{% include figure.html image="/Images/6.5-Panel-2-complete.jpeg" caption="The first two panels complete — Panel 2 demolded cleanly thanks to the hardboard insert modification that cut the resin weight in the center of the panel." %}

Phase 6 is in progress (Rev 1.6). All four steel frames were welded at the same time during Phase 1, so no new frame work is needed for panels 2–4. Panel 2 is now complete and demolded: the mold from Panel 1 was reused with four 1/8" hardboard inserts attached to bring the fiberglass bottom level with the cross bars — this reduces the resin volume pooled in the center of the panel, addressing the weight problem from the first panel, and the panel demolded cleanly from the melamine without the slow shimming and prying torque that warped Panel 1. The hardboard pieces are white-on-one-side / black-on-the-other and attached to the mold surface; the fiberglass back skin was wet out with 24 oz of resin (vs. 16 oz on Panel 1, the extra because the porous hardboard inserts absorb resin alongside the fiberglass cloth during wet-out). The resin savings from the hardboard modification come later in the Phase 4 flood coat — with the fiberglass bottom already raised to the cross-bar level, the center of the panel no longer fills with a deep resin pool. The hardboard is hygroscopic — it absorbs moisture from the air and moves with humidity at a different rate than the cured resin — but it sits on the back-skin side of the cross-bars, well clear of the solar cells, so any dimensional change should not stress the cells; once encased in resin the moisture exchange is largely cut off and it stabilizes. The back skin was de-blushed and primed, matching the Panel 1 process.

One issue with Panel 2: the hardboard inserts were not sprayed with silicone release spray before the pour, so they bonded permanently to the back of the panel and could not be removed. This was an expected risk and adds only a small amount of weight; for Panel 3, parchment paper will be tried as a release layer on the inserts.

With Panel 1 and Panel 2 both complete, the two were wired together and tested under load in non-peak sun, driving an inverter at its minimum supported voltage. The pair delivered **17.34 V at 4.06 A (~70 W)** combined — a useful output even off-peak.

After Panel 2 demolded cleanly, Panel 1 was reinspected and **5 of its 16 cells were found to be cracked.** During Panel 1's layup an air bubble was left trapped behind the panel and was never removed; that bubble expands in the heat and puts pressure on the delicate cells directly above it. Some of the cracks may also have occurred during demolding (the prying torque that warped the panel), but the trapped air is the most likely primary cause. On Panel 2 the bubble was removed during layup, and the panel will be monitored for cracks developing over time. The 5 cracked cells in Panel 1 are sealed in resin and cannot be replaced — the panel still produces power, just at a reduced output.

Phase 6 is in progress (Rev 1.10) — Panel 4 next. The shop was tied up with another project that required a long curing time to prevent "blushing" on a lacquer finish; it has since been reclaimed by the solar panel project, and Panel 3 spent the weekend in it: the cells were soldered and the resin poured. Two issues during layup: the polarity check was skipped again before laying down the strands, so the bus bars go to the opposite holes (the Panel 1 mistake repeating — the J-Box will need the same crossover fix), and one cell cracked (~2 cm × 1 cm, in the very center) while removing the air bubbles — power loss should be minor given the size and position. Panel 3 has since completed the full process — demolded and wired like the others — and all three finished panels were test-fit in the truck bed together. The final panel (4) will be different: the battery and inverter will be mounted on its bottom, with a locked access panel to gain access to the power; if any solar cells are added to it, only about 50% of the panel would be covered (8 cells). Then wire all four panels together and go camping.

---

*Upcoming sections will cover electrical configuration, battery integration, cooler wiring, and field test results as the build progresses.*

---

## Version history

| Rev | Date | Description |
|---|---|---|
| 1.0 | 2026-08-01 | Initial finalized release. |
| 1.1 | 2026-08-02 | Phase 6 started: Panel 2 layup underway (mold reused with 1/8\" hardboard inserts to cut resin weight, fiberglass wet out with 24 oz of resin). Added Phase 6 page and outcome paragraph; updated status line and phase list item 6. |
| 1.2 | 2026-08-02 | Corrected hardboard watch-out (hygroscopic moisture movement, not resin absorption) in the Phase 6 outcome paragraph. |
| 1.3 | 2026-08-02 | Corrected the 24 oz wet-out rationale in the Phase 6 outcome paragraph — the extra resin is absorbed by the porous hardboard during wet-out; the flood-coat resin savings come from the shallower center cavity, not deeper cross-bar pockets. |
| 1.4 | 2026-08-03 | Corrected the Phase 5 panel output from ~54 W to ~65 W (9.6 V × 6.76 A = 64.9 W) and the pre-resin figure from ~66 W to ~67 W (9.6 V × 6.96 A = 66.8 W) in the phase list, outcome paragraph, and status line. |
| 1.5 | 2026-08-03 | Phase 6 Panel 2 Phase 2 Step 3 complete: back skin de-blushed and primed. Updated status line, phase list item 6, and outcome paragraph. |
| 1.6 | 2026-08-14 | Phase 6 Panel 2 complete and demolded (hardboard inserts stuck to the back — not sprayed with release). Two-panel test: 17.34 V at 4.06 A (~70 W) in non-peak sun. Panel 1 inspection found 5/16 cells cracked, attributed to a trapped air bubble expanding in the heat. Updated status line, phase list item 6, and outcome paragraph. |
| 1.7 | 2026-08-14 | Corrected the two-panel test description: 17.34 V / 4.06 A was measured under load (driving an inverter at its minimum supported voltage), not open-circuit / short-circuit. Updated status line, phase list item 6, and outcome paragraph. |
| 1.8 | 2026-09-14 | Panel 3: cells soldered and resin poured after a shop delay (lacquer-blush cure on another project); polarity check skipped again (bus bars on opposite holes) and one cell cracked (~2 cm × 1 cm, center) while removing air bubbles; demold planned for the week. Panel 4 planned as battery/inverter mount with locked access panel, optionally ~8 cells covering ~50%. Updated status line, phase list item 6, and outcome paragraph. |
| 1.9 | 2026-09-14 | Replaced the first-panel figure in the Outcome section with the two-panels-complete photo (figure 6.5), matching the current build progress. |
| 1.10 | 2026-09-17 | Panel 3 complete and all three finished panels test-fit in the truck bed. Replaced the top \"Progress so far\" figure with the three-panel test-fit photo (6.11); updated status line, phase list item 6, and outcome paragraph. |

---

*Content licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) — see [LICENSE](https://github.com/wildelaw/r1t-solar-tonneau/blob/main/LICENSE).*