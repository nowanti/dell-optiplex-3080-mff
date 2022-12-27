
## Dell OptiPlex 3080 Micro (3080MFF) Hackintosh OpenCore EFI


### [简体中文](README.zh_CN.md)



### OpenCore

[OpenCore 0.8.7](https://github.com/acidanthera/OpenCorePkg)



### Spec

- Model: Dell OptiPlex 3080 MFF
- BIOS: 2.16.0
- Chipset: B460
- CPU: Intel 10th i5-10500T
- Memo: SK hynix 16GB(8GBx2) 3200 Mhz
- GPU: Intel UHD630
- 声卡: Realtek ALC3246(ALC256)
- SSD: Kioxia 512G (KBG40ZNS) m.2 2230
- LAN: Realtek RTL8111HSD-CG
- WLAN: Intel 3165



### BIOS

```
System Configuration
  |-- SATA Operaition: AHCI

Video
  |-- Primary Display: Intel HD Graphics

Intel Software Guard Extension
  |-- Intel SGX Enable: Disabled

Performance
  |-- Intel TurboBoost: YES

PowerManagement
  |-- Deep Sleep Control: Disabled
  |-- Block Sleep: YES
```



### Kexts

- [Lilu.kext 1.6.2](https://github.com/acidanthera/Lilu)
- [SMCProcessor.kext 1.3.0](https://github.com/acidanthera/VirtualSMC)
- [SMCSuperIO.kext 1.3.0](https://github.com/acidanthera/VirtualSMC)
- [SMCDellSensors.kext 1.3.0](https://github.com/acidanthera/VirtualSMC)
- [VirtualSMC.kext 1.3.0](https://github.com/acidanthera/VirtualSMC)
- [WhateverGreen.kext 1.6.2](https://github.com/acidanthera/WhateverGreen)
- [NVMeFix.kext 1.1.0](https://github.com/acidanthera/NVMeFix)
- [AppleALC.kext 1.7.7](https://github.com/acidanthera/AppleALC)
- [RealtekRTL8111.kext 2.4.2](https://github.com/Mieze/RTL8111_driver_for_OS_X)
- [USBMap.kext v1.0.0](https://github.com/corpnewt/USBMap)
- [XHCI-unsupported.kext v0.9.2](https://github.com/hackintosh-efi/XHCI-unsupported)



### Tools

- [Hackintool](https://github.com/headkaze/Hackintool) 
- [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) AKA OCC.
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) Generate SMBIOS.
- [MountEFI](https://github.com/corpnewt/MountEFI) Mount EFI partition.
- [EFI Agent](https://github.com/headkaze/EFI-Agent) Better EFI partition mount App.
- [gibMacOS](https://github.com/corpnewt/gibMacOS) Build your own MacOS image.
- [ProperTree](https://github.com/corpnewt/ProperTree) Plist editor.
