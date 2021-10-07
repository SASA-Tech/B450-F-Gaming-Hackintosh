# ASUS ROG Strix B450 F-Gaming Hackintosh
[![](https://img.shields.io/badge/Gitter%20HL%20Community-Chat-informational?style=flat&logo=gitter&logoColor=white&color=ed1965)](https://gitter.im/Hackintosh-Life-IT/community)
[![](https://img.shields.io/badge/Repository-SASATech-informational?style=flat&logo=apple&logoColor=white&color=9debeb)](https://github.com/SASA-Tech?tab=repositories)
[![](https://img.shields.io/badge/Telegram-HackintoshLifeIT-informational?style=flat&logo=telegram&logoColor=white&color=5fb659)](https://t.me/HackintoshLife_it)
[![](https://img.shields.io/badge/Facebook-HackintoshLifeIT-informational?style=flat&logo=facebook&logoColor=white&color=3a4dc9)](https://www.facebook.com/hackintoshlife/)
[![](https://img.shields.io/badge/Instagram-HackintoshLifeIT-informational?style=flat&logo=instagram&logoColor=white&color=8a178a)](https://www.instagram.com/hackintoshlife.it_official/)

#### *Leggilo in un'altra lingua: [Italiano](README.md)* :it:
## macOS Big Sur successfully installed on ASUS ROG Strix B450 F-Gaming

| Components       | Model.                                  |
| ---------------- | ----------------------------------------|
| Motherboard      | ASUS ROG Strix B450 F-Gaming            | 
| CPU              | AMD Ryzen™ 3 3200G                      | 
| GPU              | Nvidia GeForce GT 730                   |
| Audio            | Realtek ALCS1220A                       |
| RAM              | 16 Gb DDR4 2666 Mhz                     |
| NVMe             | Samsung SSD 980 500gb                   |
| SMBIOS           | MacPro7,1 (solo se avete Nvidia Kepler) |
| Bootloader       | OpenCore 0.7.4                          |

![infodp0](./Screenshot/AboutThisMac.png)

## Mobo:

![infodp1](./Screenshot/Mobo.PNG)

## By default the OC GUI is set to 1920x1080.
If you have a different resolution, go to EFI> OC, delete the Resources folder and unzip the one you need.

## Disable:

- Fast Boot
- CSM

## Enable:

- Above 4G decoding (se non lo trovate nel bios, aggiungete npci=0x2000 nei bootargs)
- EHCI/XHCI Hand-off
- OS type: Other
  
# Devices Screenshot
![infodp2](./Screenshot/PCIe.png)
![infodp3](./Screenshot/PCIe2.png)

# What works and what doesn't:
- [x] Nvidia GeForce GT 730
- [x] ALCS1220A Uscite Jack
- [x] USB Ports (Partially work)
- [x] Intel I211 Gigabit LAN
- [x] NVRAM
- [x] Boot Windows by OpenCore
- [x] SpeedStep / Sleep / Wake
- [ ] iGPU Vega 8 Graphics

# Extras

AMD Power Gadget: https://github.com/trulyspinach/SMCAMDProcessor/releases

## Change CPU model in "About This Mac" - macOS Big Sur:

In the process of writing...

## Credits

- [Acidanthera](https://github.com/acidanthera) for OpenCore Bootloader
- [Apple](https://apple.com) for macOS;
- [HackintoshLifeIT](https://github.com/Hackintoshlifeit) Support group pre and post install
- [Dortania](https://github.com/dortania) for Hackintosh guides

# If you need help contact us on [Telegram](https://t.me/HackintoshLife_it)
