# Ryzen-2700x-ASUS-B550A-Gaming-EFI-Monterey

This is the fully detailed guide on how to create a working Hackintosh machine using:

:small_blue_diamond: MacOS Monterey 12.1 <br />
:small_blue_diamond: OpenCore 0.7.9 <br />
:small_blue_diamond: Processor: AMD Ryzen 3700x 8 Core 16 Threads <br />
:small_blue_diamond: RAM: 16 GB 3200 Mhz <br />
:small_blue_diamond: Graphics: NVIDIA GTX 760 2GB DDR5 <br />
:small_blue_diamond: SSD: ADATA 256 GB  <br />
:small_blue_diamond: SMBIOS: iMacPro 1.1 2017 <br />

This repository contains also EFI folder with all binaries produced meanwhile. The missing pieces might be however serial numbers or other hardware identifiers.

# Working On Mac Os Monterey

:white_check_mark: MacOS Monterey 12.1 <br />
:white_check_mark: Processor: AMD Ryzen 3700x 8 Core 16 Threads :love_letter: (updated to latest patch for monterey)  <br />
:white_check_mark: Graphics: NVIDIA GTX 760 2GB DDR5 :warning: (should patch using geforce kepler)  <br /> 
:white_check_mark: Ehernet I225-V Added Without Kext just adding on boot args "dk.e1000=0" without quotes<br /> 
:white_check_mark: HDMI audio <br />
:white_check_mark: All USB <br />
:white_check_mark: ThunderBolt <br />


# List Tools We Need

1. [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) - Initial configuration
2. [AMD Power Gadget](https://github.com/trulyspinach/SMCAMDProcessor) - for monitoring amd ryzen
3. [Geforce Kepler Patcher](https://github.com/chris1111/Geforce-Kepler-patcher) - for patching nvidia kepler
4. [HackingTool by Headkaze](https://github.com/headkaze/Hackintool) - to verify settings on running macOS are fine; wasn't always working fine if `EFI` configuration had error on target machine


# Official Opencore

1. [OpenCore](https://dortania.github.io/OpenCore-Install-Guide/) - Opencore Official Website
