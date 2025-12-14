# Lunar-Thermal-Blanket
**Status:** Phase 0 complete · Phase 1 defined · Test-ready reference architecture

*Note: Please ensure raccoons are not sleeping under the blanket — it will be dark and warm.*

A passive, dust-tolerant lunar surface infrastructure asset that increases thermal time constants for batteries and small surface hardware using regolith-based insulation.

This repository contains a **Phase 0 / Phase 1 reference package** intended for NASA-style early-stage evaluation, SBIR alignment, and open technical review.

---

## What This Is

* A **passive thermal blanket** deployed on the lunar surface
* Uses **native regolith** as the primary insulating medium
* Treats thermal mitigation as **surface infrastructure**, not bespoke hardware design
* Scales by repetition, not complexity

---

## What This Is Not

* Not a heater
* Not a power generator
* Not a cryocooler
* Not a habitat system
* Not dust-sensitive
* Not mission-critical life-support hardware

---

## Repository Contents

```
/README.md                     ← You are here
/docs/
  Moon_Thermal_Blanket_Phase0-1.md
  Assumptions_and_Envelope.md
  Numeric_Example.md
  Failure_Tree.md
  Phase1_Test_Plan.md
  Deployment_Modes.md
  Cost_and_Scaling.md
  Mission_Fit.md
/diagrams/
  ACS2_Moon_Thermal_Blanket.txt
/license/
  LICENSE.md
```

---

## Phase 0 Summary

Phase 0 establishes:

* The problem pressure (lunar thermal extremes)
* A passive reference architecture
* Conservative physics-based justification
* Clear non-goals and prior-art positioning

No novel materials or physics are claimed. The contribution is **architectural packaging and repeatability**.

---

## Phase 1 Summary

Phase 1 defines:

* A thermal-vacuum test matrix
* Clear pass / fail criteria
* Degradation-focused risk retirement

Phase 1 success is measured by **relative improvement**, not absolute temperature claims.

---

## Why This Exists

Thermal solutions are typically re-engineered per asset. This work reframes insulation as:

> *A deployable, reusable surface infrastructure layer that multiple assets can rely on.*

This reduces integration burden, power draw, and design risk across missions.

---

## Intended Audience

* NASA / CLPS reviewers
* SBIR evaluators
* Surface systems engineers
* Thermal engineers
* Mission architects

---

## License

This repository is released under a **non-commercial open reference license**.

* Free for research, evaluation, and internal use
* Commercialization requires a separate license

See `/license/LICENSE.md` for details.

---

## Status

* Phase 0: **Complete**
* Phase 1: **Defined**
* Phase 2+: Not in scope

---

## How to Use This Repo

* Read Phase 0 for concept and framing
* Use Phase 1 to evaluate testability
* Fork for internal studies or mission trades

If this breaks, succeeds, or teaches you something — that is the point.
