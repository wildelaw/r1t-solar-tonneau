# R1T Solar Tonneau

Engineering & build log for a custom **55" × 13½" × ½" steel-framed solar panel** that replaces the tonneau cover on a Rivian R1T. The panel charges a battery backup power supply stored in the truck bed, or directly powers a cooler in the bed.

> **Status: Rev 1.6 — Phase 6 in progress** — Phases 1–5 complete (first panel). Panel 2 is built, demolded, and tested: with Panel 1 under load in non-peak sun (driving an inverter at its minimum supported voltage) the pair delivers 17.34 V at 4.06 A (~70 W); Panel 1 has 5 of 16 cells cracked from a trapped air bubble. After a shop delay, Panel 3's cells are soldered and its resin poured — one cell cracked while chasing bubbles and the polarity check was skipped again, so the bus bars land on the opposite holes. Demold is planned later this week. Panel 4 is planned as the battery/inverter mount with a locked access panel. Final four-panel wiring still to come.

## Documentation

Full build documentation is published with GitHub Pages:

**https://wildelaw.github.io/r1t-solar-tonneau/**

The site covers the build process as it progresses:

- **[Materials](https://wildelaw.github.io/r1t-solar-tonneau/materials)** — full bill of materials with resin volume math
- **[Phase 1 — Frame Prep & Bonding Surface](https://wildelaw.github.io/r1t-solar-tonneau/build/phase-1-frame-prep)** — ✅ complete — weld, flatten, prime, test-fit
- **[Phase 2 — Bottom-Up Layup & Hole Drilling](https://wildelaw.github.io/r1t-solar-tonneau/build/phase-2-layup)** — ✅ complete — fiberglass back skin, amine blush removal, drill wire exits
- **[Phase 3 — Cell Placement & Routing](https://wildelaw.github.io/r1t-solar-tonneau/build/phase-3-cells)** — ✅ complete — Kapton insulation, cell stringing, bus-bar routing, clay seal
- **[Phase 4 — The Resin Pour](https://wildelaw.github.io/r1t-solar-tonneau/build/phase-4-resin)** — ✅ complete — seal coat, flood coat, expansion gap, heat-gun bubbles, 48-hour cure
- **[Phase 5 — Post-Cure, Expansion Cap & J-Box Soldering](https://wildelaw.github.io/r1t-solar-tonneau/build/phase-5-post-cure)** — ✅ complete — demold, putty removal, expansion cap (skipped on first panel), J-Box wired + tested (9.6 V open, 6.76 A short-circuit, ~65 W), test fit in the truck bed
- **[Phase 6 — Do It Three More Times](https://wildelaw.github.io/r1t-solar-tonneau/build/phase-6-more-panels)** — 🛠️ in progress — all four frames pre-welded in Phase 1; Panel 2 complete and demolded (hardboard inserts stuck to the back — not sprayed with release); Panel 1 + Panel 2 tested together under load (driving an inverter at its minimum supported voltage): 17.34 V at 4.06 A (~70 W) in non-peak sun; Panel 1 has 5/16 cells cracked from a trapped air bubble; Panel 3 cells soldered + resin poured after a shop delay (polarity check skipped again — bus bars on opposite holes; one cell cracked ~2 cm × 1 cm while chasing bubbles), demold planned for the week; Panel 4 planned as battery/inverter mount with locked access panel; then wire all four together
- **[Pro Hints & Watch-Outs](https://wildelaw.github.io/r1t-solar-tonneau/pro-tips)** — failure modes and hard-won lessons

The canonical source document is [`Docs/Directions.md`](Docs/Directions.md).

## Project goals

- **Drop-in fit** on the R1T bed channel — sized to 54⅞" to clear the tailgate gap
- **Zero-sag structure** via a welded steel frame with three internal cross-beams
- **Weatherproof encapsulation** of solar cells in UV-stabilized marine epoxy using the *Direct Bond + Expansion Cap* method
- **Field-serviceable wiring** through a sealed IP67 junction box on the back skin
- **Bed-grade output** to feed a portable battery bank or 12V cooler

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

## License

See [LICENSE](LICENSE).

---

## Version history

| Rev | Date | Description |
|---|---|---|
| 1.0 | 2026-08-01 | Initial finalized release. |
| 1.1 | 2026-08-02 | Phase 6 started: Panel 2 layup underway (mold reused with 1/8\" hardboard inserts to cut resin weight, fiberglass wet out with 24 oz of resin). Updated status line and Phase 6 list entry. |
| 1.2 | 2026-08-03 | Corrected the Phase 5 panel output from ~54 W to ~65 W (9.6 V × 6.76 A = 64.9 W) in the Phase 5 list entry. |
| 1.3 | 2026-08-03 | Phase 6 Panel 2 Phase 2 Step 3 complete: back skin de-blushed and primed. Updated status line and Phase 6 list entry. |
| 1.4 | 2026-08-14 | Phase 6 Panel 2 complete and demolded (hardboard inserts stuck to the back — not sprayed with release). Two-panel test: 17.34 V at 4.06 A (~70 W) in non-peak sun. Panel 1 inspection found 5/16 cells cracked, attributed to a trapped air bubble expanding in the heat. Updated status line and Phase 6 list entry. |
| 1.5 | 2026-08-14 | Corrected the two-panel test description: 17.34 V / 4.06 A was measured under load (driving an inverter at its minimum supported voltage), not open-circuit / short-circuit. Updated status line and Phase 6 list entry. |
| 1.6 | 2026-09-14 | Panel 3: cells soldered + resin poured after a shop delay (lacquer-blush cure on another project); polarity check skipped again (bus bars on opposite holes) and one cell cracked (~2 cm × 1 cm) while removing air bubbles; demold planned for the week. Panel 4 planned as battery/inverter mount with locked access panel. Updated status line and Phase 6 list entry. |