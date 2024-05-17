# Ultralight-waterproof-22.5W-10000mAh-Dual-USB-C-carbon-fiber-power-bank-with-PD3.0-QC4-support
Open source design and production files for https://www.reddit.com/r/UsbCHardware/comments/1cksl2a/diy_open_source_ultralight_waterproof_225w/

This project was largely inspired by the NB10000 from Nitecore!

The power bank is based on the IP5355 from Injonic (datasheet is in chinese, use google translate) and utilizes a 9858102 3.85v 10000mAh Lithium polymer cell. The enclosure comprises of a 60mm x 12mm carbon fiber tube + PC-ABS 3D printed fittings on each end. Its weighs ~168.5g and is approximately 129.2mm x 60.0mm x 11.9mm.

To maximize water resistance, IP rated components were used as much as possible (e.g Alpine SKTDLDE010 IP67 Switch and TE 2305018-2 IPX8 USB-C Connector). The fittings at both ends are designed to have a good fit and can be hermetically sealed with adhesive/epoxy. Additional waterproofing can be achieved by applying a conformal coating to the PCB.

Both USB-C ports support up to 18W input/22.5W output fast charging via USB PD3.0 (Fixed: 12V@1.67A, 9V@2.22A, 5V@2.4A and PPS: 3.3V-11.0V@2.00A) and other protocols* (QC2.0/QC3.0/QC3+/QC4+**, BC1.2, Apple 5V@2.4A, AFC, SCP, FCP)

*Doesn't support QC for fast charging input

**QC4+ support is present when tested even though not explicitly stated in the datasheet

Includes design (Schematics, PCBs, 3D Models) and production files (Gerbers, BOM, PicknPlace)

EasyEDA Pro project file (.epro) can be imported into KiCad v8.0 and above

Disclaimer: Lithium batteries are inherently dangerous. Improper handling may result in fire, explosion, damage to property, injuries or death. Please take the necessary care and precautions when handling lithium batteries. All materials in this repository are experimental in nature and are provided AS IS, without any warranty, explicit or implied, including but not limited to warranties of merchantability, safety or fitness for a particular purpose. By using materials contained in this repository, you agree that you do so AT YOUR OWN RISK. 

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]
This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
