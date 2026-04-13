# Buffer Solution Assistant

`Buffer Solution Assistant` is a Windows desktop GUI for preparing common lab buffers with practical calculation steps and guidance.

It supports:
- **Tris-HCl** recipe calculation
- **PBS** recipe calculation (NaH2PO4/Na2HPO4, optional NaCl/KCl)
- **Tris-HCl + EDTA ± NaCl** calculation with ionic-strength-aware notes

The packaged release includes an installer built with Inno Setup.

## What The App Does

The app helps estimate:
- required reagent masses (for example Tris, EDTA salts, phosphate salts, NaCl, KCl)
- acid addition volumes (HCl stock solution volume)
- practical recipe output text suitable for bench use

It is intended as a **calculation aid**, not a replacement for SOPs, risk assessments, instrument calibration, or supervisory approval.

## Scope And Assumptions

The calculation model is designed to get you **close to target pH in one shot** under typical room-temperature preparation conditions.

Assumptions include:
- preparation near **25 °C** (room temperature)
- use of pKa and related constants appropriate to that temperature range
- idealized behavior relative to real laboratory solutions

Because real conditions vary, users should expect some deviation from the requested pH and concentration. Small corrections (for example final pH adjustment with acid/base) may still be required based on actual:
- temperature
- ionic strength
- reagent lot/purity/age
- meter calibration and measurement technique

In short: the app aims to reduce iteration and get you near your target quickly, but it does not guarantee exact final pH without bench verification and adjustment.

## Quick Start (Installed Version)

1. Download `BufferSolutionAssistantSetup.exe` from the release assets.
2. Run the installer and complete setup.
3. Launch **Buffer Solution Assistant** from Start Menu or desktop shortcut.
4. Choose a buffer type on the first screen.
5. Enter target parameters and follow on-screen steps to generate a recipe.
6. Verify pH experimentally and adjust according to your lab protocol.

## Quick Start (Portable EXE)

If you use the standalone EXE (not installer):
- Keep `Buffer Solution Assistant.exe`, `Logo.png`, and `Icon.ico` together in the same folder.
- Launch the EXE directly.

## Safety Reminder

This software does **not** eliminate chemical hazards. Always:
- follow your institution's biosafety and chemical hygiene rules
- use required PPE (lab coat, gloves, eye protection, and other PPE per protocol)
- handle strong acids/bases (including concentrated HCl) in appropriate engineering controls (for example a fume hood)
- label containers clearly with contents, concentration, date, and operator
- verify pH and concentration with calibrated equipment before use in experiments

## Waste Handling And Regulatory Compliance

All preparation, storage, and disposal must comply with:
- local, regional, and national regulations
- your institution's EHS procedures
- project-specific biosafety/chemical waste SOPs

Do not dispose of chemical or biological waste down drains unless explicitly permitted by approved local procedures.

## Disclaimer

This application is provided "as is" for educational and laboratory workflow support. Users are responsible for validating calculations, confirming reagent identity/purity, and ensuring safe, compliant experimental practice.

## Media Attribution (Installer Wizard Image)

The installer wizard image uses a DNA illustration derived from:
- Wikimedia Commons: [File:DNA-molecule2.jpg](https://commons.wikimedia.org/wiki/File:DNA-molecule2.jpg)
- Original source: [Dna rendering (Flickr)](https://www.flickr.com/photos/91887854@N00/1531699476/)
- Author: **ynse** (Poland)
- License: [Creative Commons Attribution-ShareAlike 2.0 Generic (CC BY-SA 2.0)](https://creativecommons.org/licenses/by-sa/2.0/)

If you redistribute this installer or modify the image, you must provide attribution and share derivative works under the same or a compatible license, consistent with CC BY-SA 2.0 terms.

This README can also be accessed from the program directory after installation. 
