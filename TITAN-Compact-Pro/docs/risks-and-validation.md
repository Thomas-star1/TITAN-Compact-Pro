# Risks and validation

| Risk | Severity | Validation / mitigation |
|---|---|---|
| No access to mobile SoC BSP or vendor support | Critical | Confirm supported access path before choosing a platform |
| Unverified or incorrectly named SoC | High | Verify exact product through official vendor sources |
| Camera sensor lacks ISP/HAL support | Critical | Written platform support and reference-hardware test |
| Active stylus incompatible with panel/digitizer | High | Confirm controller, protocol, drivers, and mechanical storage |
| 8 mm body target conflicts with battery/cameras/stylus | High | CAD stack-up before component commitment |
| Silicon-carbon cell unavailable in suitable size or with reliable documentation | High | Compare traceable qualified cells and safety data |
| Thermal throttling or uncomfortable surface temperature | High | Power budget, thermal model, and prototype tests |
| Cellular RF or antenna performance fails | Critical | Authorized RF design and lab testing |
| Certification or carrier requirements exceed budget | High | Identify target market and applicable requirements early |
| Cost and minimum order quantities are unrealistic | High | Obtain written quotations and MOQ details |
| Security updates cannot be maintained | Critical | Require an explicit support and update strategy |
| Student project lacks legal/commercial eligibility | Medium/High | Ask vendor about eligibility; involve a responsible adult when contracts are involved |

## Evidence checklist before any purchase

- [ ] Exact part number and official datasheet.
- [ ] Electrical interfaces and voltage requirements.
- [ ] Mechanical dimensions and connector details.
- [ ] Driver, firmware, BSP, HAL, and licensing status.
- [ ] Confirmed compatibility with the selected platform.
- [ ] Supplier identity, traceability, sample policy, and MOQ.
- [ ] Cost, shipping, taxes, lead time, and return/warranty terms.
- [ ] Safety and regulatory documentation where applicable.

## Spending rule

Do not purchase expensive phone components merely because a listing says “for Android” or “compatible with Snapdragon.” Obtain technical confirmation and a supported integration plan first.
