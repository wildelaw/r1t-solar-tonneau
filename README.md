# R1T Solar Tonneau

Engineering & build log for a custom **55" × 13½" × ½" steel-framed solar panel** that replaces the tonneau cover on a Rivian R1T. The panel charges a battery backup power supply stored in the truck bed, or directly powers a cooler in the bed.

> **Status: In Progress** — Phase 1 (Frame Prep & Bonding Surface) is complete. Phases 2–5 are planned and may change based on actual experience. Work on Phase 2 begins shortly after July 4, 2026.

## Documentation

Full build documentation is published with GitHub Pages:

**https://wildelaw.github.io/r1t-solar-tonneau/**

The site covers the build process as it progresses:

- **[Materials](https://wildelaw.github.io/r1t-solar-tonneau/materials)** — full bill of materials with resin volume math
- **[Phase 1 — Frame Prep & Bonding Surface](https://wildelaw.github.io/r1t-solar-tonneau/build/phase-1-frame-prep)** — ✅ complete — weld, flatten, prime, test-fit
- **[Phase 2 — Bottom-Up Layup & Hole Drilling](https://wildelaw.github.io/r1t-solar-tonneau/build/phase-2-layup)** — planned — fiberglass back skin, amine blush removal, drill wire exits
- **[Phase 3 — Cell Placement & Routing](https://wildelaw.github.io/r1t-solar-tonneau/build/phase-3-cells)** — planned — Kapton insulation, cell stringing, bus-bar routing, clay seal
- **[Phase 4 — The Resin Pour](https://wildelaw.github.io/r1t-solar-tonneau/build/phase-4-resin)** — planned — seal coat, flood coat, expansion gap, torch bubbles, cure
- **[Phase 5 — Post-Cure, Expansion Cap & J-Box Soldering](https://wildelaw.github.io/r1t-solar-tonneau/build/phase-5-post-cure)** — planned — demold, clay removal, silicone cap, J-Box solder
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