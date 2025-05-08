# Notebook Lenovo B40-70 + i5 4200u + HD4400
	
![about](https://raw.githubusercontent.com/skaterfel/EFI-Notebook-Lenovo-B40_70-i5_4200u-HD4400/refs/heads/main/Infos/about-this-mac.png)
	

**Latest working macOS**: 12.7.4
<br>
**Current OpenCore**: 1.0.0

## Complete hardware specs
- DualCore Intel Core i5-4200U | 4th Haswell 
- Lenovo B40-70 - [BIOS 9DCN34WW(V3.04)
- Intel(R) HD Graphics 4400 (1 GB) - 8086/0A16
- 1x 8GB + 1x 4GB DDR3 1600
- Wifi/BT replaced by Fenvi BCM94360NG - Work OOB

## What works
- macOS Monterey (no test in macOS Big Sur, macOS Catalina and )
- Audio
- HDMI/DP (in dGPU - Works OOB)
- All USB ports
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything except GPU
- DRM content (Netflix, ATV+, Airplay 2 mirroring etc)
- Shutdown/Reboot/Update to newer macOS builds over time
- Sleep
- TrackPad: Cursor movement



## What doesn't work
- Wifi and BlueTooth (I no have Fenvi chip for tests)
- TrackPad: Gestures, Clicks


## Kexts used:
- AppleALC.kext
- Lilu.kext
- SMCSuperIO.kext	
- SMCProcessor.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext
- BrightnessKeys.kext
- CpuTscSync.kext
- ECEnabler.kext
- FeatureUnlock.kext
- RealtekRTL8111.kext
- RestrictEvents.kext
- USBWakeFixup.kext
- VoodooInput.kext
- VoodooPS2Controller.kext
- VoodooSMBus.kext


## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI - for 11th Intel Gen - Rocket Lake](https://github.com/luchina-gabriel/BASE-EFI-INTEL-DESKTOP-11THGEN-ROCKET-LAKE)
- tonymacx86.com - in special @etorix and @CaseySJ

## Discord - Universo Hackintosh
- [Access Discord](https://discordapp.com/users/skaterfel)
