# Prosthetics Summer Project

A summer engineering project to design and fabricate a low-cost, passive prosthetic finger device for individuals with partial hand amputations.

---

## Goal

Design, prototype, and iterate on a passive prosthetic finger that:
- Restores basic hand function (grip, pinch, lateral) for partial-hand amputees
- Can be fabricated with accessible tools (3D printing + silicone casting)
- Is custom-fitted to the patient's residual limb anatomy
- Minimises cost compared to commercial alternatives (e.g. Naked Prosthetics MCP Driver)

---

## Final Product

A cable-driven passive prosthetic finger assembly consisting of:

| Component | Description |
|---|---|
| 3D printed chassis | Structural frame anchored to the dorsal surface of the hand |
| Hand support | Wrist/hand brace that holds the device in place |
| Artificial silicone fingers | Cosmetic and functional outer layer |
| Proximal phalanx | First finger segment, connected to chassis |
| Intermediate phalanx | Middle finger segment |
| Distal phalanx | Fingertip segment |
| Hinge joints | PIP and DIP joints linking phalanges |
| Cable | Tension cable running through phalanges to drive flexion |
| Orthodontic rubber bands | Passive extension return mechanism |

The device mimics natural finger motion: flexion is driven by the patient's residual hand input through the cable; extension is returned passively by the rubber bands.

---

## Project Summary

This project draws on published research and commercial designs (notably the Naked Prosthetics MCP Driver) to produce an open, iteratable prosthetic finger design. Work covers:

1. **Research** — reviewing existing passive prosthetic finger literature and commercial products
2. **3D scanning** — capturing the patient's residual limb geometry for custom fit
3. **CAD design** — modelling phalanges, hinges, and chassis in STEP format
4. **3D printing** — fabricating structural components
5. **Silicone casting** — producing the cosmetic/functional outer finger
6. **Assembly & testing** — iterating on fit, range of motion, and grip strength

Current design version: **V3** (outer phalange) / **V2** (hinge)

---

## Tech Stack

| Tool | Purpose |
|---|---|
| CAD software (STEP output) | Parametric design of phalanges, hinges, chassis |
| 3D printer (FDM) | Fabricating structural parts |
| 3D scanner | Capturing residual limb geometry for custom fit |
| Silicone casting | Producing artificial finger cosmesis |
| GitHub | Version control for CAD files, documentation, and research notes |

---

## Repository Structure

```
.
├── cad/
│   ├── step-files/        # STEP files for all designed components
│   └── 3d-models/         # STL / print-ready models
├── scans/                 # 3D scan data of residual limb
├── photos/
│   ├── arm/               # Photos of the patient's arm / fit
│   └── misc/              # Build progress, assembly photos
├── docs/                  # Research notes, references, design decisions
└── research/              # Papers, competitor analysis, inspiration
```

---

## Component Versions

| Component | Current Version | File |
|---|---|---|
| Outer phalange | V3 | `cad/step-files/V3 Outer phalange.STEP` |
| Hinge | V2 | `cad/step-files/V2 Hinge.STEP` |

---

## References

- [Naked Prosthetics — MCP Driver](https://www.npdevices.com/components/mcp-driver/) — commercial benchmark for proximal phalange amputation prosthetics
- Literature on cable-driven passive prosthetic fingers (see `research/`)
