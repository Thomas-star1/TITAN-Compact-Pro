# Camera system

**Status:** Requirements and validation plan only. No module is confirmed compatible.

## Intended arrangement

1. Main camera — everyday photography.
2. Ultrawide camera — wider field of view.
3. Telephoto camera — target around 3× optical magnification, with autofocus and OIS.

The industrial-design direction is a raised rounded-square camera island with a triangular lens arrangement. The final layout must follow real module dimensions, optical clearances, flash, microphones, and motherboard placement.

## Required module data

For each candidate, record:
- Manufacturer and exact part number.
- Official datasheet and revision/date.
- Sensor format, resolution, pixel size, and supported modes.
- Lens focal length or equivalent field of view; do not confuse digital zoom with optical magnification.
- Autofocus actuator and OIS details.
- Module dimensions and optical center.
- Interface (for example, MIPI CSI-2), lane configuration, clocking, and power rails.
- Driver, firmware, tuning data, and Camera HAL availability.
- Minimum order quantity, lead time, sample availability, and traceability.
- Evidence of compatibility with the chosen SoC/BSP.

## Integration risks

- A sensor may be electrically connectable but unsupported by the platform ISP or software.
- OIS and autofocus need control interfaces and drivers.
- Optical performance depends on lens, sensor, calibration, tuning, and mechanical alignment.
- Telephoto modules can require more depth than the thin body target permits.
- Three cameras increase board area, power, thermal load, calibration work, and cost.

## Validation sequence

1. Obtain authoritative datasheets.
2. Verify platform vendor support for the exact sensor/module.
3. Confirm module dimensions and optical requirements.
4. Review power, interface, drivers, HAL, and tuning.
5. Test on supported reference hardware before committing to custom mechanics.
6. Validate image quality, autofocus, OIS, thermal behavior, and low-light performance.
