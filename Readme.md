# tacx_neo_rev_eng

Welcome to the **tacx_neo_rev_eng** repository. This project serves as a collaborative workspace for the **reverse engineering** of the TACX NEO SMART trainer's internal electronics.

## Project Status: Draft

This is currently a **work-in-progress** and should be considered a draft. The primary goal is to document the hardware architecture to better understand the trainer's power management and communication protocols.

### Contents

* **High-Resolution Photographs:** Detailed imagery of the TACX NEO SMART trainer PCB.
* **Schematic Sketch:** Simplified schematic of the PCB, which shows mostly the power supply
* *Note: These schematics are currently **incomplete** and may contain placeholders*

### General disassembly

For disassembly of this trainer a special tool from Garmin or a 3D printed tool is needed.

The following removal tool have been used for this project
* Tacx Neo Disc remover by sutnup (https://www.thingiverse.com/thing:2748489)
    * Bolt M16x60 DIN933
    * Nut M16 DIN934
    * Bolt M6x16 DIN912

### Known issues

#### Diode D3 of +12V buck converter U1

* Description: Trainer does not start any longer and the fans spin continously.
* Failure mode: This buck converter is known to fail due to diode D3. (DFLS1100)

### Disclaimer

This project is for educational and diagnostic purposes only. Messing with your trainer's internals may void your warranty or lead to hardware failure. Proceed with caution!