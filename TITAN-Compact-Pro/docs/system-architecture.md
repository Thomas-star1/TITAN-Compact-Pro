# System architecture

**Status:** Conceptual only. Component compatibility has not been established.

```text
Custom Android / AOSP-based OS
  ├─ System UI and settings
  ├─ Active-stylus input services
  ├─ Android Camera Framework / Camera HAL
  ├─ Connectivity and telephony framework
  └─ OTA and security-update strategy
             |
Vendor BSP / kernel / drivers / firmware
             |
Mobile SoC platform
  ├─ CPU / GPU / NPU
  ├─ ISP and camera interfaces
  ├─ Memory and storage interfaces
  ├─ Display and touch interfaces
  └─ Modem/connectivity interfaces (platform-dependent)
             |
Custom motherboard
  ├─ RAM and storage
  ├─ PMIC, charging, fuel gauge, protection
  ├─ RF front-end, antennas, SIM/eSIM
  ├─ USB and peripheral interfaces
  └─ Debug and production-test access
             |
Physical modules
  ├─ OLED panel + digitizer
  ├─ Active stylus + controller
  ├─ Main, ultrawide, telephoto cameras
  ├─ Battery and charging system
  ├─ Speakers, microphones, haptics, sensors
  └─ Frame, thermal spreader, camera assembly
```

## Critical dependency chain

1. Identify a platform genuinely available for a custom device.
2. Confirm BSP, kernel, firmware, security, camera, display, modem, and RF access.
3. Obtain platform documentation and reference design through an authorized route.
4. Validate component candidates against interfaces and software requirements.
5. Create mechanical CAD and component stack-up.
6. Review power, thermal, antenna, battery safety, and manufacturing constraints.
7. Prototype and test with qualified engineering support.
8. Plan certification, production testing, OTA updates, and long-term security maintenance.

## Architecture rules

- Do not choose a SoC only by benchmark performance.
- Do not assume Android can be ported without required proprietary binaries, drivers, signing keys, and vendor support.
- Camera modules are not interchangeable by default; drivers, tuning, actuators, ISP, and HAL matter.
- Keep vendor claims and decisions traceable.
- Treat secure boot, verified boot, firmware updates, device identity, and vulnerability response as requirements.
