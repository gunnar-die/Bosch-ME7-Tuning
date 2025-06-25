---
# Enhanced Readme for GitHub

## Custom Engine Tunes and Definitions

This repository contains custom engine tunes and definition files primarily for the **8E0919518AK** ECU, cross compatible with the **8E0919518BC** ECU with modifications for enhanced performance using minimal hardware upgrades. These were developed using a healthy rebuilt 1.8t AMB engine, rebuilt AWM small port head, with all hardware left stock aside from a B7 dual side mount intercooler set, SAI delete, and 386cc injectors.

---

### 8E0919518AK_91_386cc_BAM_Fueling_V5.bin

This tune is an advanced **Stage 1 calibration**, building upon the foundation of a Nefmoto Stage 1 file. It has been meticulously adjusted for:

* **91 Octane Fuel**: Enhanced **LAMFA** for richer fueling and precise timing adjustments to optimize performance with 91 octane fuel.
* **Reduced IAT Timing Pull**: Slightly decreased timing reduction based on Intake Air Temperatures (IATs) for more consistent power delivery in varying conditions.
* **BAM Injector Adaptation**: Fueling tables specifically recalibrated for the **386cc injectors** from the BAM 225hp engine.
* **4 Bar Returnless Fuel System**: Adjusted for a 4 Bar returnless fuel system, diverging from the BAM's stock 3 Bar return system.

---

### 8E0909518AK_368072_Stock_SAIoff_386cc_sum.bin

This file serves as my **"eco" tune** and a critical **benchmarking reference**. It is essentially the stock AK file, but with key adaptations:

* **386cc BAM Injector Support**: Calibrated to properly utilize 386cc injectors from the BAM engine.
* **SAI Delete**: Modified to disable the Secondary Air Injection (SAI) system, ideal for vehicles with SAI removed.

---

### 8E0909518AK_368072_TylerW_CDSLS_fix.xdf

This is a **TunerPro definition file (.xdf)**, refined from TylerW's original compilation. It includes a crucial fix for:

* **CDSLS Location Correction**: Addresses an incorrectly mapped CDSLS location for modifying SAI, correcting it from 0x181AD to the accurate address of **0x181B0**.

---
