# ASUS ROG Strix B450 F-Gaming Hackintosh
[![](https://img.shields.io/badge/Gitter%20HL%20Community-Chat-informational?style=flat&logo=gitter&logoColor=white&color=ed1965)](https://gitter.im/Hackintosh-Life-IT/community)
[![](https://img.shields.io/badge/Repository-SASATech-informational?style=flat&logo=apple&logoColor=white&color=9debeb)](https://github.com/SASA-Tech?tab=repositories)
[![](https://img.shields.io/badge/Telegram-HackintoshLifeIT-informational?style=flat&logo=telegram&logoColor=white&color=5fb659)](https://t.me/HackintoshLife_it)
[![](https://img.shields.io/badge/Facebook-HackintoshLifeIT-informational?style=flat&logo=facebook&logoColor=white&color=3a4dc9)](https://www.facebook.com/hackintoshlife/)
[![](https://img.shields.io/badge/Instagram-HackintoshLifeIT-informational?style=flat&logo=instagram&logoColor=white&color=8a178a)](https://www.instagram.com/hackintoshlife.it_official/)
#### *Write this in other language: [English](README.EN.md)* :us:
# Italian Repository 🇮🇹
## macOS Big Sur correttamente installato su ASUS ROG Strix B450 F-Gaming

| Componenti       | Modello                                 |
| ---------------- | ----------------------------------------|
| Scheda Madre     | ASUS ROG Strix B450 F-Gaming            | 
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

## Di default la GUI di OC è impostata in 1920x1080.
Se avete una risoluzione diversa, recatevi in EFI > OC, cancellate la cartella Resources e scompattate quella che vi interessa.

# Impostazioni Bios

## Disabilita:

- Fast Boot
- CSM

## Abilita:

- Above 4G decoding (se non lo trovate nel bios, aggiungete npci=0x2000 nei bootargs)
- EHCI/XHCI Hand-off
- OS type: Other
  
# Dispositivo Screenshot
![infodp2](./Screenshot/PCIe.png)
![infodp3](./Screenshot/PCIe2.png)

# Cosa funziona e cosa no:
- [x] Nvidia GeForce GT 730
- [x] ALCS1220A Uscite Jack
- [x] Porte USB (Funzionano parzialmente)
- [x] Intel I211 Gigabit LAN
- [x] NVRAM
- [x] Avvio Windows da OpenCore
- [x] SpeedStep / Sleep / Wake
- [ ] iGPU Vega 8 Graphics

# Extras

AMD Power Gadget: https://github.com/trulyspinach/SMCAMDProcessor/releases

## Cambiare modello CPU in "About This Mac" - macOS Big Sur:

In fase di scrittura...

## Crediti

- [Acidanthera](https://github.com/acidanthera) per OpenCore Bootloader
- [Apple](https://apple.com) per macOS;
- [HackintoshLifeIT](https://github.com/Hackintoshlifeit) Gruppo di supporto pre e post installazione
- [Dortania](https://github.com/dortania) per le guide Hackintosh

# Se avete bisogno di aiuto contattateci su [Telegram](https://t.me/HackintoshLife_it)
