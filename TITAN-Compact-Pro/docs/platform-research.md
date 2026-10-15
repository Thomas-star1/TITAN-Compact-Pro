# Mobile platform research

**Goal:** Establish whether the project can obtain a supported platform for a custom Android smartphone.

## Minimum platform requirements

| Requirement | Why it matters | Evidence needed |
|---|---|---|
| SoC sourcing/access | A chip name or retail phone is not an integration path | Written vendor/authorized-partner confirmation |
| Android BSP | Board-specific Android integration | Supported Android versions and delivery terms |
| Kernel and drivers | Hardware requires supported drivers | Kernel branch, driver availability, support period |
| Camera ISP/HAL | Cameras need platform-specific integration and tuning | Camera documentation, HAL/BSP availability, tuning process |
| Display/touch | Panel interfaces and digitizer must be supported | Interface details and driver support |
| Modem/RF | Cellular requires firmware, RF design, bands, and regulatory work | Reference design and authorized integration path |
| Security | Boot chain, keys, patches, and updates must be maintainable | Security architecture and update policy |
| Reference design | Reduces integration uncertainty | Availability, licensing, and support terms |
| Commercial terms | Development access may have costs and eligibility requirements | Written terms, minimums, NDA/licensing requirements |

## Vendor inquiry checklist

Ask the platform vendor or authorized design partner:
1. Do you support independent/student-led exploratory projects, or must the requester be a registered company?
2. Is the named mobile platform available for a new custom smartphone design?
3. Which BSP, kernel, drivers, firmware, camera HAL/ISP materials, and reference designs are available?
4. What are the eligibility criteria, NDA/licensing terms, minimum order quantities, and engineering costs?
5. Is there an authorized design/manufacturing partner suitable for a low-volume feasibility prototype?
6. What Android version and security-update support window are realistic?
7. Which display, stylus/digitizer, camera, memory, storage, and RF components are already validated?

## Decision gate

**Do not commit to a SoC** until access, software deliverables, licensing, security maintenance, and a supported integration path are confirmed in writing.

The project has not yet confirmed any Qualcomm or other vendor support. Product naming and availability must be checked against official vendor documentation; do not assume an unverified chipset designation is real or accessible.
