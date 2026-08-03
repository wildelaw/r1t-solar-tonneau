---
layout: page
title: "Phase 6 — Do It Three More Times"
nav_order: 7
---

# Phase 6: Do It Three More Times

> **Status: In progress (Panel 2).** All four steel frames are already welded, so Phase 1 work for panels 2–4 is complete. Panel 2 is currently in its Phase 2 layup — the same mold is being reused with a hardboard insert modification to reduce resin weight, and the fiberglass back skin has been wet out (24 oz of resin). This page tracks the build progress of the remaining three panels and the final wiring of all four together.

The truck bed needs four panels. The first panel is built (Phases 1–5 complete); this phase covers repeating the process for panels 2, 3, and 4, then wiring them all together.

## Panel tracker

| Panel | Phase 1 — Frame | Phase 2 — Layup | Phase 3 — Cells | Phase 4 — Resin | Phase 5 — Post-Cure | Status |
|---|---|---|---|---|---|---|
| 1 | ✅ | ✅ | ✅ | ✅ | ✅ | Complete |
| 2 | ✅ (pre-welded) | 🛠️ In progress | — | — | — | Layup |
| 3 | ✅ (pre-welded) | — | — | — | — | Not started |
| 4 | ✅ (pre-welded) | — | — | — | — | Not started |

All four frames were welded at the same time during Phase 1, so no additional Phase 1 work is planned for panels 2–4.

## Panel 2 — Phase 2: Layup

### Mold prep — reused, with hardboard inserts

The same mold from Panel 1 is being reused. **Modification for Panel 2:** Four 1/8" hardboard panels were attached to the mold to bring the fiberglass bottom level with the cross bars, which reduces the resin volume pooled in the center of the panel. The first panel came out heavier than ideal (see the weight note in [Phase 5 — Demold]({{ site.baseurl }}{% link build/phase-5-post-cure.md %}#1-demold)); leveling the bottom skin against the cross-bars cuts the center resin depth and the overall panel mass.

The hardboard pieces are white on one side and black on the other, attached to the mold surface. If the panel de-molds cleanly and the hardboard releases intact, the same inserts will be reused for panels 3 and 4.

{% include figure.html image="/Images/6.1-Hardboard-inserts-in-mold.jpeg" caption="Four 1/8\" hardboard inserts attached to the mold to level the fiberglass bottom with the cross bars, reducing the resin volume in the center of the panel." %}

### Fiberglass wet-out

The fiberglass was wet out with **24 oz of resin** (vs. 16 oz on Panel 1 — the extra accounts for sealing around the hardboard inserts and the deeper cross-bar pockets).

{% include figure.html image="/Images/6.2-Fiberglass-wet-out-24oz.jpeg" caption="Fiberglass wet out with 24 oz of resin in the modified mold." %}

> **Watch-out — hardboard dimensional stability:** Hardboard is hygroscopic — it absorbs moisture from the air and expands/contracts with humidity at a different rate than the cured epoxy around it. The inserts are on the back-skin side of the cross-bars, well clear of the solar cells, so any dimensional change should not stress the cells. Once the hardboard is fully encased in resin, moisture exchange with the air is largely cut off and it stabilizes; worst case it ends up sealed in resin and adds a small amount of weight.

### Next steps for Panel 2

- Let the back skin cure 24 hours.
- Remove amine blush and paint the back skin (same as Panel 1, Phase 2 Step 3).
- Drill wire exits (this time in Phase 2, before soldering cells — the deferred-drilling lesson from Panel 1).
- De-mold the hardboard inserts and evaluate whether they are reusable for Panel 3.

## Wiring all four panels together

*(To be documented once the remaining panels are built. The plan is to wire the four panels into the R1T bed channel and connect them via MC4 connectors to the Harbor Freight Predator power bank through an Anderson adapter — see Phase 5 for the connector plan.)*

---

Previous: **[Phase 5 — Post-Cure, Expansion Cap & J-Box Soldering]({{ site.baseurl }}{% link build/phase-5-post-cure.md %})**
Next: **[Pro Hints & Watch-Outs]({{ site.baseurl }}{% link pro-tips.md %})**

---

## Version history

| Rev | Date | Description |
|---|---|---|
| 1.0 | 2026-08-02 | Initial release. Panel 2 Phase 2 started: mold reused with 4× 1/8\" hardboard inserts to level the fiberglass bottom with the cross bars, fiberglass wet out with 24 oz of resin. Panel tracker table added. |
| 1.1 | 2026-08-02 | Corrected the hardboard watch-out — hardboard is hygroscopic (absorbs air moisture and moves with humidity at a different rate than the cured resin), not resin-absorbing; once encased in resin it stabilizes. |

---

*Content licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) — see [LICENSE](https://github.com/wildelaw/r1t-solar-tonneau/blob/main/LICENSE).*