# Assumptions and Reference Operating Envelope

This document defines the baseline assumptions and operating envelope used throughout the Lunar Thermal Blanket Phase 0 / Phase 1 reference architecture. These assumptions are intentionally conservative and expressed as ranges.

---

## 1. Scope and Intent

* These assumptions support **Phase 0 credibility** and **Phase 1 test planning**.
* Values are not guarantees for all lunar micro-sites.
* The envelope is designed to be broadly representative rather than optimized.

Unless explicitly stated otherwise, all Phase 0 analysis assumes the **baseline case** defined in this document.

---

## 2. Site Classification

### Class E — Equatorial / Mid-Latitude Surface (Baseline)

* Long lunar night (~14 Earth days)
* Large diurnal temperature swing
* Direct view to space during night
* Representative of many general-purpose surface assets

**Phase 0 baseline assumes Class E.**

---

### Class P — Polar / Near-Polar (Non-PSR)

* Lower average temperatures
* Intermittent solar illumination
* Long night effects still relevant

The Lunar Thermal Blanket provides benefit but may require combination with other thermal strategies.

---

### Class S — Shadow-Adjacent / High-Risk Cold Zones

* Persistent or near-persistent cold
* Extreme radiative losses

The blanket functions as a **time-constant extender**, not a standalone survival solution.

---

## 3. Environmental Temperature Ranges

Representative surface temperature ranges used for modeling and test selection:

* **Daytime:** ~0°C to +120°C
* **Nighttime:** ~-130°C to -170°C

Actual temperatures vary based on:

* Local albedo
* Surface slope
* Illumination geometry
* Regolith properties

---

## 4. Day / Night Cadence

* Lunar synodic cycle: ~29.5 Earth days
* Typical surface experience:

  * ~14 Earth days daylight
  * ~14 Earth days night

Phase 0 modeling focuses on **nighttime survival and cooldown behavior**.

---

## 5. Thermal Reservoir Classes

The Lunar Thermal Blanket protects a *thermal reservoir* (battery or hardware enclosure). Phase 0 analysis uses the following representative classes:

### R1 — Small Reservoir

* Approximate effective thermal mass: 5–20 kg
* Typical use: sensors, small robots, instrument packages

---

### R2 — Medium Reservoir (Baseline)

* Approximate effective thermal mass: 20–80 kg
* Typical use: rover battery modules, compact lander subsystems

**Phase 0 baseline assumes R2.**

---

### R3 — Large Reservoir

* Approximate effective thermal mass: 80–250+ kg
* Typical use: stationary power nodes, surface infrastructure elements

---

## 6. Performance Metrics

All performance is measured **relative to an unprotected baseline**.

Primary metrics:

* **τ (thermal time constant):** τ = R_eff × C
* **τ_gain:** Ratio of τ with blanket to τ without blanket
* **Δt_survival:** Additional time before minimum allowable temperature is reached
* **ΔT_peak_day:** Reduction in daytime peak reservoir temperature

---

## 7. Non-Goals and Exclusions

The following are explicitly out of scope:

* Maintaining room-temperature conditions
* Eliminating all active thermal systems
* Precision thermal isolation
* Mission-critical life-support thermal control

The Lunar Thermal Blanket is an **infrastructure-level risk reducer**, not a complete thermal solution.

---

## 8. Assumption Discipline

If an analysis, test, or discussion:

* Violates these assumptions, or
* Requires substantially different environmental conditions

That deviation must be stated explicitly.

---

## Status

Applies to:

* Phase 0 reference architecture
* Phase 1 test planning
