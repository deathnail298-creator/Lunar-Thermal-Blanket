# Failure Tree and Degradation Analysis

This document enumerates credible failure modes and degradation pathways for the Lunar Thermal Blanket. The focus is on **graceful degradation** rather than binary failure, consistent with infrastructure-class assets.

---

## 1. Failure Philosophy

The Lunar Thermal Blanket is intentionally:

* Passive
* Geometry-driven
* Free of moving parts and active control

As a result, most failures reduce performance gradually rather than causing total loss of function.

---

## 2. Primary Failure Modes

### F1 — Partial Blanket Displacement

**Cause:**

* Regolith settling
* Local slope creep
* Minor impact events

**Effect:**

* Increased edge losses
* Reduced effective R_eff

**Outcome:**

* Gradual reduction in thermal time constant τ
* Continued partial functionality

**Mitigation:**

* Over-coverage margin
* Skirt geometry
* Acceptance of non-uniform regolith thickness

---

### F2 — Blanket Puncture or Perforation

**Cause:**

* Micrometeoroid impacts
* Abrasive regolith particles

**Effect:**

* Localized radiative leak paths

**Outcome:**

* Minor localized degradation
* Regolith remains dominant insulation mechanism

**Mitigation:**

* Non-critical structural layer
* No reliance on pressure retention or sealing

---

### F3 — Dust Infiltration Beneath Radiant Underlayer

**Cause:**

* Deployment disturbance
* Thermal cycling

**Effect:**

* Degraded radiant properties of optional underlayer

**Outcome:**

* Neutral or beneficial insulation behavior

**Mitigation:**

* Design does not rely on pristine reflective surfaces

---

### F4 — Thermal Interface Plate Misalignment

**Cause:**

* Initial placement error
* Post-deployment settling

**Effect:**

* Reduced conductive coupling to insulated region

**Outcome:**

* Reduced benefit without total loss

**Mitigation:**

* Oversized contact area
* Flexible conductive straps

---

### F5 — Excessive Daytime Heat Trapping

**Cause:**

* High local albedo
* Favorable solar incidence geometry

**Effect:**

* Elevated peak reservoir temperature

**Outcome:**

* Reduced daytime margin

**Mitigation:**

* Vent paths in skirt geometry
* Geometry tuned to avoid sealed cavities

---

## 3. Long-Term Degradation Modes

### D1 — Regolith Compaction Over Time

* Improves contact and insulation
* Considered beneficial

---

### D2 — Structural Material Aging

* Slow degradation under radiation and thermal cycling
* No moving parts to seize or bind

---

### D3 — Repeated Thermal Cycling

* Gradual performance drift expected
* Measured as τ reduction, not failure

---

## 4. Failure Classification Summary

| Failure Mode | Severity | Behavior              |
| ------------ | -------- | --------------------- |
| F1           | Low      | Graceful degradation  |
| F2           | Low      | Localized degradation |
| F3           | Very Low | Neutral / beneficial  |
| F4           | Medium   | Performance reduction |
| F5           | Medium   | Geometry-tunable      |

No identified single-point failures cause total system loss.

---

## 5. Phase 1 Risk Retirement

Phase 1 testing will explicitly:

* Induce partial displacement
* Introduce dust contamination
* Cycle temperatures repeatedly
* Measure τ drift over cycles

Success is defined as **predictable degradation**, not zero degradation.

---

## Status

Supports:

* Phase 0 reference architecture
* Phase 1 validation and risk retirement
