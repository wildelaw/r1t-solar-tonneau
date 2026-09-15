---
layout: page
title: "Phase 6 — Do It Three More Times"
nav_order: 7
---

# Phase 6: Do It Three More Times

> **Status: In progress (Panel 3 — resin poured).** Panel 2 is complete and tested (17.34 V at 4.06 A ~70 W under load with Panel 1; Panel 1 has 5/16 cells cracked from a trapped air bubble). After a shop delay (another project needed a long cure to prevent lacquer blushing), the shop is back on solar-panel duty: Panel 3's cells were soldered and the resin poured over the weekend. The bus bars land on the opposite holes — the polarity check was skipped again — and one cell cracked (small 2 cm × 1 cm center crack) while removing the air bubbles. Demold is planned for later this week. The final panel (4) is planned as the mounting point for the battery and inverter, with a locked access panel. This page tracks the build progress of the remaining panels and the final wiring of all four together.

The truck bed needs four panels. The first panel is built (Phases 1–5 complete); this phase covers repeating the process for panels 2, 3, and 4, then wiring them all together.

## Panel tracker

| Panel | Phase 1 — Frame | Phase 2 — Layup | Phase 3 — Cells | Phase 4 — Resin | Phase 5 — Post-Cure | Status |
|---|---|---|---|---|---|---|
| 1 | ✅ | ✅ | ✅ | ✅ | ✅ | Complete (5/16 cells cracked) |
| 2 | ✅ (pre-welded) | ✅ | ✅ | ✅ | ✅ | Complete (hardboard inserts stuck to back) |
| 3 | ✅ (pre-welded) | ✅ | ✅ | ✅ | — | Resin poured — demold planned this week |
| 4 | ✅ (pre-welded) | — | — | — | — | Planned — battery/inverter mount + locked access panel |

All four frames were welded at the same time during Phase 1, so no additional Phase 1 work is planned for panels 2–4.

## Panel 2 — Phase 2: Layup

### Mold prep — reused, with hardboard inserts

The same mold from Panel 1 is being reused. **Modification for Panel 2:** Four 1/8" hardboard panels were attached to the mold to bring the fiberglass bottom level with the cross bars, which reduces the resin volume pooled in the center of the panel. The first panel came out heavier than ideal (see the weight note in [Phase 5 — Demold]({{ site.baseurl }}{% link build/phase-5-post-cure.md %}#1-demold)); leveling the bottom skin against the cross-bars cuts the center resin depth and the overall panel mass.

The hardboard pieces are white on one side and black on the other, attached to the mold surface. If the panel de-molds cleanly and the hardboard releases intact, the same inserts will be reused for panels 3 and 4.

{% include figure.html image="/Images/6.1-Hardboard-inserts-in-mold.jpeg" caption="Four 1/8\" hardboard inserts attached to the mold to level the fiberglass bottom with the cross bars, reducing the resin volume in the center of the panel." %}

### Fiberglass wet-out

The fiberglass was wet out with **24 oz of resin** (vs. 16 oz on Panel 1 — the extra accounts for the porous hardboard inserts absorbing resin alongside the fiberglass cloth during wet-out). The resin savings from the hardboard modification come later, in the Phase 4 flood coat: with the fiberglass bottom already raised to the cross-bar level, the center of the panel no longer fills with a deep resin pool.

{% include figure.html image="/Images/6.2-Fiberglass-wet-out-24oz.jpeg" caption="Fiberglass wet out with 24 oz of resin in the modified mold." %}

> **Watch-out — hardboard dimensional stability:** Hardboard is hygroscopic — it absorbs moisture from the air and expands/contracts with humidity at a different rate than the cured epoxy around it. The inserts are on the back-skin side of the cross-bars, well clear of the solar cells, so any dimensional change should not stress the cells. Once the hardboard is fully encased in resin, moisture exchange with the air is largely cut off and it stabilizes; worst case it ends up sealed in resin and adds a small amount of weight.

### Back skin — de-blushed and primed

The cured back skin has been washed to remove the amine blush and primed with a coat of epoxy paint, matching the Panel 1 process (see [Phase 2 — Step 3]({{ site.baseurl }}{% link build/phase-2-layup.md %}#3-remove-amine-blush--paint-back-skin)).

{% include figure.html image="/Images/6.3-Blush-removed.jpeg" caption="Back skin washed with warm water, dish soap, and a Scotch-Brite pad to remove the amine blush." %}
{% include figure.html image="/Images/6.4-Primered-back-skin.jpeg" caption="Primer coat applied over the de-blushed back skin." %}

The wire exits were drilled in Phase 2 this time, before soldering cells — the deferred-drilling lesson from Panel 1 applied.

## Panel 2 — Phase 5: Demold & Test

### Demold — hardboard inserts

The hardboard inserts worked exactly as intended for demolding the panel from the main mold: the panel lifted cleanly off the melamine without the slow shimming and prying torque that warped Panel 1 (see [Phase 5 — Demold]({{ site.baseurl }}{% link build/phase-5-post-cure.md %}#1-demold)). The inserts raised the fiberglass bottom level with the cross bars and cut the center resin pool, so the panel came out lighter.

However, I failed to spray the hardboard inserts with silicone release spray before the pour. As a result the hardboard bonded to the back of Panel 2 and could not be removed — it is now permanently attached to the bottom of the panel. This was an expected risk and is acceptable (the hardboard adds a small amount of weight but sits clear of the cells). For Panel 3 I will try lining the inserts with extra-wide parchment paper to see if that helps release them intact.

{% include figure.html image="/Images/6.8-Hardboard-stuck-to-panel-2.jpeg" caption="Hardboard inserts bonded permanently to the back of Panel 2 — they were not sprayed with silicone release before the pour. For Panel 3, parchment paper will be tried as a release layer." %}

### Panel 2 complete

{% include figure.html image="/Images/6.5-Panel-2-complete.jpeg" caption="Panel 2 complete and demolded — the hardboard insert modification reduced the resin weight in the center of the panel." %}

### Two-panel test

With Panel 1 and Panel 2 both complete, the two were wired together and tested under load in non-peak sun, driving an inverter at its minimum supported voltage. The pair delivered **17.34 V at 4.06 A (~70 W)** — a useful combined output even off-peak.

{% include figure.html image="/Images/6.6-Both-panels-17v.jpeg" caption="Panel 1 and Panel 2 wired together under load (driving an inverter at its minimum supported voltage) in non-peak sun: 17.34 V." %}
{% include figure.html image="/Images/6.7-Both-panels-4.06a.jpeg" caption="Panel 1 and Panel 2 wired together under load in non-peak sun: 4.06 A. Combined output ~70 W." %}

## Panel 1 — post-build inspection: cell cracks from trapped air

After Panel 2 was demolded cleanly, I went back and inspected Panel 1 more closely. **5 of the 16 cells in Panel 1 are cracked.** During Panel 1's layup, an air bubble was left trapped behind the panel and was never removed; that bubble expands in the heat and puts pressure on the delicate cells. Some of the cracks may also have occurred during demolding (the prying torque that warped the panel — see [Phase 5 — Demold]({{ site.baseurl }}{% link build/phase-5-post-cure.md %}#1-demold)), but the trapped air is the most likely primary cause for the cells directly over the bubble.

**Lesson for next panels:** Remove every trapped air bubble during layup before the resin cures. On Panel 2 the bubble was removed, and the panel will be monitored for any cracks developing over time. The existing 5 cracked cells in Panel 1 are sealed in resin and cannot be replaced — the panel still produces power (it contributed to the 17.34 V / 4.06 A under-load two-panel test above), just at a reduced output.

> **Watch-out — trapped air behind the panel:** An air bubble left behind a panel during layup is not just a cosmetic issue. In the sun the trapped air heats up and expands, bowing the panel and putting pressure on the fragile solar cells directly above it — enough to crack them over time. Chase and release every trapped air pocket before the resin gels.

## Panel 3 — Layup, Cells & Resin Pour

### A delayed start

The mold shop was tied up with another project that required a long curing time to prevent "blushing" on a lacquer finish. The shop has since been reclaimed by the solar panel project, and Panel 3 spent the weekend in it: the cells were soldered and the resin poured.

### Cells soldered — polarity check skipped (again)

{% include figure.html image="/Images/6.9-Panel-3-cells-soldered.jpeg" caption="Panel 3 cells soldered up — the bus bars land on the opposite holes from Panel 1 because the polarity was not checked before laying down the strands." %}

You may notice the bus bars go to the *opposite* holes: someone (me) forgot to check the polarity before laying down the strands — the same mistake from Panel 1 (see [Pro Hints & Watch-Outs]({{ site.baseurl }}{% link pro-tips.md %})). The wiring will need the same crossover fix at the J-Box that Panel 1 needed.

### One cell cracked while chasing bubbles

Removing the air bubbles cracked one cell — a small ~2 cm × 1 cm crack in the very center of one cell. The power loss should be minor given the size and position. Panel 3 becomes the second panel with a sealed-in crack, joining Panel 1 (5 cracked cells) — and a reminder that the resin locks in whatever happens during layup.

### Resin poured

{% include figure.html image="/Images/6.10-Panel-3-resin-pour.jpeg" caption="Resin poured on Panel 3, following the same seal-coat / flood-coat process as the previous panels." %}

The resin is poured and curing. Demold is planned for later this week.

## Panel 4 — the final panel

The last panel will be different from the first three: it will be the mounting point for the battery and the inverter, mounted on its bottom, with a locked access panel to gain access to the power. If any solar cells are added to it, only about 50% of the panel would be covered (8 cells) — the rest of the space goes to the power hardware.

## Next steps

- Demold Panel 3 later this week (watch how the hardboard inserts release this time — silicone release and parchment paper were the planned fixes for the stuck-insert problem).
- Wire Panel 4: battery and inverter mount on the bottom, locked access panel, optionally ~8 cells covering ~50%.
- Wire all four panels together.

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
| 1.2 | 2026-08-02 | Corrected the 24 oz wet-out rationale — the extra resin is absorbed by the porous hardboard inserts during wet-out; the resin savings come later in the Phase 4 flood coat (shallower center cavity), not from deeper cross-bar pockets. |
| 1.3 | 2026-08-03 | Panel 2 Phase 2 Step 3 complete: back skin de-blushed and primed. Added figures 6.3 and 6.4, updated next-steps and status banner. |
| 1.4 | 2026-08-14 | Panel 2 complete and demolded (hardboard inserts stuck to the back — not sprayed with release). Two-panel test in non-peak sun: 17.34 V and 4.06 A (~70 W). Panel 1 inspection found 5/16 cells cracked, attributed to a trapped air bubble expanding in the heat. Added figures 6.5 (panel 2 complete), 6.6 (17.34 V), 6.7 (4.06 A), 6.8 (hardboard stuck to panel 2); updated panel tracker, status banner, and next steps for Panel 3. |
| 1.5 | 2026-08-14 | Corrected the two-panel test description: 17.34 V / 4.06 A was measured under load (driving an inverter at its minimum supported voltage), not open-circuit / short-circuit. Updated the two-panel test section, figure captions, status banner, and lesson paragraph. |
| 1.6 | 2026-09-14 | Panel 3: cells soldered and resin poured after a shop delay (lacquer-blush cure on another project). Bus bars landed on the opposite holes — polarity check skipped before laying strands; one cell cracked (~2 cm × 1 cm, center) while removing air bubbles. Added figures 6.9 and 6.10. Panel 4 planned as battery/inverter mount with locked access panel (optionally ~8 cells covering ~50%). Updated tracker, status banner, and next steps. |

---

*Content licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) — see [LICENSE](https://github.com/wildelaw/r1t-solar-tonneau/blob/main/LICENSE).*