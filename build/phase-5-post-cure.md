---
layout: page
title: "Phase 5 — Post-Cure, Expansion Cap & J-Box Soldering"
nav_order: 6
---

# Phase 5: Post-Cure, Expansion Cap & J-Box Soldering

> **Status: In progress — may change based on actual experience.** Steps 1–2 complete (demold + putty removal). Step 3 skipped for the first panel. Step 4 blocked on a J-Box fit issue. Steps are being revised as the work progresses.

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

## 4. Mount the J-Box (blocked)

*Not yet done — blocked on a wiring-fit issue.*

**Observation:** The cell alignment from Phase 1 put the positive and negative wires in positions that are swapped relative to the junction box I purchased — the bus wires will not reach the terminals cleanly, and the box will not fit the current wire spacing while still allowing the panel to slide into the truck bed's cover slots.

**Update — two options being evaluated:**
1. Pick up a different junction box that fits the current wire spacing and still clears the bed cover slots.
2. Mount the current box sideways and route the bus wires so they do not touch.

Will update this step once a path is chosen.

---

Previous: **[Phase 4 — The Resin Pour]({{ site.baseurl }}{% link build/phase-4-resin.md %})**
Next: **[Pro Hints & Watch-Outs]({{ site.baseurl }}{% link pro-tips.md %})**

> **Note:** Once this phase is done, the first panel is finished — but the truck bed needs four. Head back to Phase 1 and repeat the whole process three more times, then wire the panels together.

---

*Content licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) — see [LICENSE](https://github.com/wildelaw/r1t-solar-tonneau/blob/main/LICENSE).*