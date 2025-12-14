# Conservative Numeric Example

This document provides a single, intentionally conservative numeric example to anchor the Phase 0 claims for the Lunar Thermal Blanket. The purpose is to demonstrate order-of-magnitude behavior, not optimized performance.

---

## 1. Intent and Discipline

* Numbers are deliberately pessimistic
* No internal waste heat is assumed
* Results are reported as **relative improvement**, not absolute survivability

This example supports Phase 0 credibility and informs Phase 1 test expectations.

---

## 2. Baseline Assumptions

**Site Class:** E (equatorial / mid-latitude)
**Reservoir Class:** R2 (medium)

**Thermal Reservoir:**

* Effective thermal mass (battery + enclosure + attached plate): **40 kg**
* Effective specific heat (lumped): **~900 J/kg·K** (metal-dominant, conservative)

Thermal capacitance:

C = m × c = 40 kg × 900 J/kg·K = **36,000 J/K**

---

## 3. Nighttime Environment (Simplified Worst Case)

* Effective environmental temperature (radiative sink): **-150°C**
* Initial reservoir temperature at sunset: **-10°C**
* Minimum allowable reservoir temperature: **-40°C**

Allowable temperature drop:

ΔT_allow = 30 K

Total initial temperature difference:

ΔT_total = 140 K

---

## 4. Case A — Unprotected Baseline (No Blanket)

Assume a pessimistic but plausible effective thermal resistance:

R_eff,baseline ≈ **0.25 K/W**

Thermal time constant:

τ_baseline = R × C = 0.25 × 36,000 ≈ **9,000 s ≈ 2.5 hours**

Fraction of total temperature drop allowed:

f = ΔT_allow / ΔT_total ≈ 30 / 140 ≈ **0.21**

Time to minimum allowable temperature (first-order exponential approximation):

t_baseline ≈ −τ · ln(1 − f) ≈ 0.24τ ≈ **0.6 hours**

This illustrates why unprotected surface batteries experience rapid cooldown after lunar sunset.

---

## 5. Case B — With Blanket (Minimal Improvement Assumed)

Assume the Lunar Thermal Blanket increases effective thermal resistance by only **2×**:

R_eff,blanket ≈ **0.5 K/W**

Thermal time constant:

τ_blanket = 0.5 × 36,000 ≈ **18,000 s ≈ 5 hours**

Time to minimum allowable temperature:

t_blanket ≈ 0.24τ ≈ **1.2 hours**

---

## 6. Interpretation

* **τ_gain = 2×** under deliberately modest assumptions
* **Δt_survival ≈ +0.6 hours** in a highly pessimistic configuration

This example intentionally understates performance:

* No internal heat generation
* Very cold effective sink temperature
* Low assumed thermal resistance values

In practice:

* Larger reservoirs (R3) increase C significantly
* Even small waste heat shifts curves meaningfully
* Increased regolith thickness can plausibly increase R_eff beyond 2×

---

## 7. Phase 1 Measurement Tie-In

Phase 1 testing will:

* Measure τ directly from temperature vs. time curves
* Compare baseline and blanket configurations
* Report τ_gain and Δt_survival empirically

No extrapolation beyond measured data is implied.

---

## Status

Supports:

* Phase 0 reference architecture
* Phase 1 test planning
