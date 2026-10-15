# Product requirements and specifications

**Status:** Initial targets, not a final engineering specification.

## Industrial design

| Requirement | Current target | Status / validation |
|---|---|---|
| Display | Approximately 6.3-inch OLED | TARGET; panel dimensions and aspect ratio TBD |
| Height | 155–160 mm | TARGET; requires CAD and stack-up |
| Width | 73–76 mm | TARGET; includes frame and tolerances |
| Body thickness | Maximum 8 mm, excluding camera protrusion | TARGET; difficult with stylus, battery, cameras, and thermal needs |
| Stylus storage | Integrated at bottom edge | TARGET; mechanism and electronics TBD |
| Rear cameras | Main, ultrawide, telephoto | TARGET |
| Camera styling | Raised rounded-square island with triangular lens arrangement and original TITAN identity | DESIGN DIRECTION |

## Display and stylus

- OLED panel with a compatible touch digitizer/controller.
- Active stylus is a core requirement.
- Protocol, pressure levels, latency, palm rejection, buttons, charging/storage method, and software support remain OPEN QUESTIONS.
- A generic stylus cannot be assumed to work with an arbitrary panel. Panel, digitizer, controller, firmware, drivers, and OS integration must be compatible.

## Camera system

- Main camera: sensor and lens TBD.
- Ultrawide camera: sensor and lens TBD.
- Telephoto target: approximately 3× optical, autofocus, and OIS.
- Each module requires verification of physical dimensions, sensor interface, power rails, actuator control, ISP compatibility, tuning data, driver availability, and Android Camera HAL support.

## Compute and software

- Target OS: custom Android-based system using AOSP where feasible.
- SoC: not selected or validated.
- Required platform support includes Android BSP, kernel, device trees, firmware/vendor binaries, secure boot, modem/RF integration, camera HAL, and security updates.
- A consumer phone chip is not automatically available for custom motherboard integration.

## Battery and power

- Preferred chemistry: silicon-carbon, only if a suitable, traceable, safe cell can be integrated.
- Priorities: cycle life, safety, supplier quality, and charging behavior—not capacity alone.
- Capacity, voltage, dimensions, protection, charging IC, fuel gauge, thermal sensors, and charging limits are TBD.
- Do not select a battery without a datasheet and safety documentation.

## Connectivity

Validate cellular bands, modem support, SIM/eSIM, Wi-Fi, Bluetooth, GNSS, NFC, USB, antennas, RF coexistence, emergency calling, regional regulations, and carrier acceptance.

## Acceptance principle

A requirement is met only when supported by objective evidence: a datasheet, written supplier confirmation, validated CAD/stack-up, prototype test, or engineering review.
