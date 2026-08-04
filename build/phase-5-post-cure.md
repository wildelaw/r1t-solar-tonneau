---
layout: page
title: "Phase 5 — Post-Cure, Expansion Cap & J-Box Soldering"
nav_order: 6
---

# Phase 5: Post-Cure, Expansion Cap & J-Box Soldering

> **Status: Complete (Rev 1.0).** All five steps done for the first panel: demold, putty removal, expansion cap (skipped on the first panel), J-Box wired + tested in the sun (9.6 V open, 6.76 A short-circuit, ~65 W), and test fit of three frames + completed panel in the truck bed.

## 1. Demold

Start by removing the temporary silicone sealing the frame to the mold, then lift the panel off the melamine board. Flip it over. You will see the plumber's putty mounds (covered with Kapton tape) on the back, with the flat bus wires sticking out.

{% include figure.html image="/Images/5.1-Demold-start.jpeg" caption="Starting to demold the panel — temporary silicone removed from the frame." %}

**Observation:** While removing the temporary silicone, I noticed that one corner of the frame was not flush against the mold, and the resin level in that corner came out lower than the rest of the panel. These kinds of issues were expected.

**Update for next panel:** Press the frame edges flush against the melamine board before sealing so this does not happen again.

{% include figure.html image="/Images/5.2-Corner-not-flush.jpeg" caption="Corner of the frame lifted away from the mold, with a lower resin level in that area." %}

### Full demold

**Observation:** Demolding took more effort than expected. The resin had bonded to the melamine in spots where the board had scuffed — instead of releasing cleanly, it broke off patches and required slowly lifting all the edges and working shims under the frame. The torque needed to pry the panel free was enough to leave a warp in the panel where those scuffed spots held on.

{% include figure.html image="/Images/5.3-Demold-complete.jpeg" caption="Panel fully demolded — took slow shimming of all edges to release." %}
{% include figure.html image="/Images/5.4-Warp-from-demold.jpeg" caption="Warp in the panel caused by the prying torque where the resin had bonded to scuffed spots on the melamine." %}

**Observation:** I considered using a silicone easy-release spray on the melamine before the next pour, but decided against it — there was too much risk of the spray getting on the steel frame and breaking the chemical bond between the resin and the primed frame. Better to accept the occasional scuff than to risk a delamination.

### Weight

**Observation:** After demolding, the panel is heavier than ideal. At the current mass, a good speed bump could be enough to worsen the warp.

**Update for next panels:** For the first panel I will add a steel L-beam across the bottom to support the ½"-deep epoxy and steel frame. For future panels I am looking at cutting the epoxy resin volume roughly in half — same coverage, less mass, less warp risk.

## 2. Remove the Putty

Peel off the Kapton tape and pick the plumber's putty out of the holes. **Observation:** It peeled away cleanly, leaving sealed, flush holes around the bus wires. (If you used non-sulfur modeling clay instead, the same applies — pick it out cleanly.)

## 3. The Expansion Cap (skipped on the first panel)

**Observation:** *Skipped on the first panel.* The expansion cap was needed with the original C-rail frame design, but I moved to the much cheaper L-beam frame, which does not require it.

**Update for next panels:** Revisit this step if the resin-to-frame interface shows cracking.

*(Original planned step, kept for reference: Flip the panel back over (sun-side up). Run a smooth bead of marine silicone into the 1/16" empty gap between the cured resin and the top edge of the steel frame. Tool it smooth with a gloved finger. This flexible cap allows the steel to expand in the heat without cracking the rigid resin.)*

## 4. Wire the J-Box

Used red shrink-tube to cross over the two − and + leads to align with the polarity of the junction box, and attached the box with white construction adhesive, including the final soldering as seen below. These panels will use standard MC4 connectors and an adapter to the Anderson connector used by the Harbor Freight Predator power bank.

{% include figure.html image="/Images/5.6-Shrink-tube-crossover.jpeg" caption="Red shrink-tube crossover routing the + and − bus wires to match the junction box polarity, bonded with white construction adhesive and final-soldered." %}

### Testing before closing the box

After soldering and before snapping on the cover, I tested the panel in the sun.

{% include figure.html image="/Images/5.7-Open-voltage-9.6v.jpeg" caption="Open-circuit voltage test in the sun: 9.6 V." %}
{% include figure.html image="/Images/5.8-Short-circuit-6.76a.jpeg" caption="Short-circuit current test in the sun: 6.76 A." %}

**Observation — lower than expected current:** Based on the test prior to enclosing in resin, this panel should have read 6.96 A.

{% include figure.html image="/Images/5.9-Pre-resin-6.96a.jpeg" caption="Pre-resin test: 6.96 A short-circuit current, before the cells were enclosed." %}

Two cells cracked during demolding, which accounts for some of the loss; the resin may also be blocking a portion of the light. Either way, 65 W is better than 0 W, but it would have been better at the 67 W (closer to the 72 W max rated per panel).

## 5. Test Fit in the Truck Bed

Installed the three to-be-done panel frames plus the one completed panel in the truck bed.

{% include figure.html image="/Images/5.10-Test-fit-in-bed.jpeg" caption="Three unfinished frames plus the one completed panel test-fit in the truck bed." %}

**Observation:** Everything still fit — no need to grind anything down for clearances. As noted during demolding, the completed frame now sags a little in the center (~1/8").

{% include figure.html image="/Images/5.11-Frame-sag.jpeg" caption="~1/8\" sag in the center of the completed frame." %}

**Update for next panels:** The weight needs to be decreased for the next one (see the weight note in Step 1).

---

Previous: **[Phase 4 — The Resin Pour]({{ site.baseurl }}{% link build/phase-4-resin.md %})**
Next: **[Pro Hints & Watch-Outs]({{ site.baseurl }}{% link pro-tips.md %})**

> **Note:** Once this phase is done, the first panel is finished — but the truck bed needs four. Head back to Phase 1 and repeat the whole process three more times, then wire the panels together.

---

## Version history

| Rev | Date | Description |
|---|---|---|
| 1.0 | 2026-08-01 | Initial finalized release. |
| 1.1 | 2026-08-03 | Corrected the panel output from ~54 W to ~65 W (9.6 V × 6.76 A = 64.9 W) and the pre-resin reference from 66 W to 67 W (9.6 V × 6.96 A = 66.8 W) in the status banner and the testing observation. |

---

*Content licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) — see [LICENSE](https://github.com/wildelaw/r1t-solar-tonneau/blob/main/LICENSE).*