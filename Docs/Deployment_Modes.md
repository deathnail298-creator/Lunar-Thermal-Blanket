# Deployment Modes and Integration Paths

This document defines credible deployment approaches for the Lunar Thermal Blanket. Deployment is treated as an operational detail rather than a core system dependency.

---

## 1. Deployment Principles

* One-time deployment
* No precision alignment required
* No moving parts after placement
* Tolerant of placement error and regolith settling

The blanket is designed to perform adequately across a range of deployment qualities.

---

## 2. Deployment Modes

### DPL-1 — Crew-Assisted Placement

**Description:**

* Blanket is manually unrolled or positioned over target area
* Regolith is placed using simple tools (rakes, scoops)

**Advantages:**

* Lowest mechanical complexity
* High adaptability to local terrain

**Limitations:**

* Requires crew presence

**Use Cases:**

* Artemis surface missions
* Early infrastructure emplacement

---

### DPL-2 — Robotic Placement (Rover or Arm-Assisted)

**Description:**

* Blanket package carried by rover or lander-mounted arm
* Blanket is dropped or unfolded over target region
* Regolith is pushed into place using blades, scoops, or wheel action

**Advantages:**

* No crew required
* Compatible with existing robotic systems

**Limitations:**

* Slower placement
* Reduced adaptability compared to crew

**Use Cases:**

* Robotic precursor missions
* Logistics buildup phases

---

### DPL-3 — Passive Drop and Self-Settling

**Description:**

* Blanket is deployed flat without immediate regolith placement
* Relies on plume fallout, later disturbances, or gradual regolith migration

**Advantages:**

* Minimal deployment energy
* Extremely low complexity

**Limitations:**

* Slower to reach full thermal performance

**Use Cases:**

* Long-duration infrastructure
* Non-time-critical assets

---

## 3. Integration With Surface Assets

The Lunar Thermal Blanket integrates with surface systems via:

* Passive thermal interface plate or straps

No electrical, data, or control interfaces are required.

Protected assets may include:

* Battery enclosures
* Power distribution nodes
* Small equipment shelters

---

## 4. Deployment Risk Summary

| Risk             | Impact | Mitigation                       |
| ---------------- | ------ | -------------------------------- |
| Misplacement     | Low    | Over-coverage margin             |
| Uneven burial    | Low    | Geometry tolerance               |
| Partial coverage | Medium | Graceful performance degradation |

No deployment mode introduces a single-point mission failure.

---

## Status

Supports:

* Phase 0 reference architecture
* Phase 1 operational realism
