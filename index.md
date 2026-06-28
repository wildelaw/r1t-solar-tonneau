---
layout: home
title: "Home"
nav_order: 0
---

# Rivian R1T Solar Tonneau Cover

An engineering & build log for a custom **55" × 13½" × ½" steel-framed solar panel** that replaces the tonneau cover on a Rivian R1T. The panel charges a battery backup power supply stored in the truck bed, or directly powers a cooler in the bed.

---

## Project goals

- **Drop-in fit** on the R1T bed channel — sized to 54⅞" to clear the tailgate gap.
- **Zero-sag structure** via a welded steel frame with three internal cross-beams.
- **Weatherproof encapsulation** of solar cells in UV-stabilized marine epoxy using the *Direct Bond + Expansion Cap* method.
- **Field-serviceable wiring** through a sealed IP67 junction box on the back skin.
- **Bed-grade output** to feed a portable battery bank or 12V cooler.

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

1. **[Phase 1 — Frame Prep & Bonding Surface]({% link build/phase-1-frame-prep.md %})** — weld, flatten, prime, test-fit in the bed.
2. **[Phase 2 — Bottom-Up Layup & Hole Drilling]({% link build/phase-2-layup.md %})** — fiberglass back skin, amine blush removal, drill wire exits.
3. **[Phase 3 — Cell Placement & Routing]({% link build/phase-3-cells.md %})** — Kapton insulation, cell stringing, bus-bar routing, clay seal.
4. **[Phase 4 — The Resin Pour (Direct Bond Method)]({% link build/phase-4-resin.md %})** — seal coat, flood coat, 1/16" expansion gap, torch bubbles, cure.
5. **[Phase 5 — Post-Cure, Expansion Cap & J-Box Soldering]({% link build/phase-5-post-cure.md %})** — demold, clay removal, silicone cap, J-Box solder.

## Reference

- **[Materials list]({% link materials.md %})** — full bill of materials with resin volume math.
- **[Pro hints & watch-outs]({% link pro-tips.md %})** — failure modes and hard-won lessons.
- **[Original directions](https://github.com/wildelaw/r1t-solar-tonneau/blob/main/Docs/Directions.md)** — canonical source document in `Docs/Directions.md`.

## Outcome

Final bed fit verified — panel sits flush in the bed channel with a clean gap at the tailgate end, ready for the resin pour and cell stringing phase.

{% include figure.html image="/Images/4.6-Bed-full-fit.jpeg" caption="Final panel alignment and fit inspection in the R1T bed." %}

---

*Future sections will cover electrical configuration, battery integration, cooler wiring, and field test results.*