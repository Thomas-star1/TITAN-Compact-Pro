# TITAN Compact Pro

**Research and feasibility study for a compact custom Android smartphone with an integrated active stylus.**

> **Status:** Concept / feasibility research. No prototype has been built, no components have been purchased, and no supplier compatibility has been confirmed.

## Vision

TITAN Compact Pro explores the feasibility of a compact, daily-use Android phone with these design goals:

- Approximately 6.3-inch OLED display.
- Target dimensions: 155–160 mm tall, 73–76 mm wide.
- Target body thickness: up to 8 mm, excluding the camera protrusion.
- Active stylus stored inside the bottom edge.
- Three rear cameras: main, ultrawide, and telephoto.
- Telephoto target: approximately 3× optical magnification, autofocus, and optical image stabilization (OIS).
- Silicon-carbon battery chemistry, if a suitable safe and traceable cell can be integrated.
- Custom Android-based software using AOSP where feasible.
- Distinct TITAN industrial design and camera-island identity.

These are **targets, not validated specifications**.

## Current phase

The project is investigating platform feasibility, software access, component compatibility, mechanical constraints, safety, certification, and realistic costs.

### Highest-priority unknowns

1. Can an independent project obtain a suitable mobile SoC platform?
2. Can it obtain the required Android BSP, kernel, drivers, firmware, camera ISP/HAL, modem/RF support, and security-update path?
3. Is an authorized design partner or reference design available?
4. Can the active stylus, OLED/digitizer, cameras, and SoC work together?
5. Can thermal, antenna, battery, manufacturing, certification, and budget constraints be met?

## Documentation

- [Specifications](docs/specifications.md)
- [System architecture](docs/system-architecture.md)
- [Platform research](docs/platform-research.md)
- [Camera system](docs/camera-system.md)
- [Roadmap](docs/roadmap.md)
- [Risks and validation](docs/risks-and-validation.md)
- [Component research register](docs/component-register.md)
- [Supplier inquiry draft](docs/supplier-inquiry.md)
- [Decision log](docs/decision-log.md)

## Evidence labels

- **CONFIRMED** — supported by an authoritative datasheet, written supplier confirmation, or test result.
- **CANDIDATE** — a possible option not yet validated for this design.
- **TARGET** — a desired requirement.
- **OPEN QUESTION** — unresolved information needed for a decision.
- **REJECTED** — investigated and ruled out, with a reason recorded.

Never present a candidate component as compatible until electrical, mechanical, software, sourcing, and licensing requirements have been checked.

## Scope and safety

This repository is research documentation, not a manufacturing package, electrical schematic, validated bill of materials, or guarantee of access to proprietary materials. Mobile SoC integration often requires authorized partners, specialized engineering, and legal agreements.

Do not commit passwords, API keys, identity documents, private correspondence, or confidential supplier materials. Do not publish proprietary documents without permission. Battery, RF, thermal, charging, and electrical designs require qualified engineering review and applicable testing.

This is an independent student-led research project. It does not represent an incorporated company or imply a partnership with any supplier.
