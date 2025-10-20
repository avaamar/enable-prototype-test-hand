# Prototype Test Hand (Phoenix UnLimbited)

This repository documents a **prototype “test hand”** based on the e-NABLE **Phoenix UnLimbited** design.  
It was fabricated by the makers as a **validation and practice prototype**, used to verify print settings, material behavior, and assembly procedures before producing a final, scaled device.

This project is intended solely for educational and research purposes.  
It is **not a certified medical device**.

---

## Purpose
The test hand served as a full workflow validation:
- To ensure all mechanical components, hinges, and elastic routing performed correctly.
- To verify assembly sequence, tolerances, and motion range before scaling to a recipient-specific size.
- To familiarise makers with e-NABLE’s open hardware design standards and printing workflows.

---

## References (official)
- e-NABLE France — “Test Hand / Download the Files”: official Phoenix UnLimbited OpenSCAD and STL resources.  
- e-NABLE global documentation: [enablingthefuture.org](https://enablingthefuture.org).

---

## Printing Parameters
- **Material:** PLA or PETG (PETG preferred for long-term testing)  
- **Layer height:** 0.2 mm  
- **Perimeters:** 3 to 4  
- **Infill:** 25–45 % gyroid  
- **Top/bottom thickness:** ≥ 1.0 mm  
- **Supports:** as indicated per part in `PrintProfiles/`  
- **Printer scaling:** 1:1 for standard e-NABLE test hand

---

## Assembly Overview
- Assemble following Phoenix UnLimbited guidelines.  
- Install cords and elastics according to e-NABLE tensioning procedure.  
- Verify hinge freedom and return spring behavior.  
- Document fit, friction points, and any tolerance corrections in `Validation/`.

---

## Validation Summary
This prototype was **built and evaluated by the makers** to confirm:
- correct joint articulation,  
- elastic routing and return,  
- durability under repeated open/close cycles.

Results of these validation tests and photos are stored in `Validation/` and `Photos/`.

---

## Bill of Materials
See `BOM/` for a complete CSV list of printed parts, fasteners, and assembly materials.

---

## Licensing and Credits
- Original design: Phoenix UnLimbited by the e-NABLE community.  
- Documentation and photos in this repository: CC BY 4.0.  
- Hardware files inherit the original open-hardware license.  
- Makers acknowledge and credit the e-NABLE design team.

---

## Disclaimer
This is a non-medical prototype for validation only.  
Use at your own risk and comply with local guidelines for assistive devices.
