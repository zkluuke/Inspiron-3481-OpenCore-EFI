# Dell Inspiron 3481 OpenCore/Hackintosh EFI
[![OpenCore](https://img.shields.io/badge/OpenCore-0.9.7-red.svg)](https://github.com/acidanthera/OpenCorePkg/releases/latest)

Complete EFI folder to hackintosh on the Dell Inspiron 14 3481
Tested with the macOS versions:
- macOS Big Sur
- macOS Monterey
- macOS Ventura
- macOS Sonoma (You need to generate another SMBIOS for it to work, you can use MacBookPro15,3 for it)


![Screenshot 2024-01-09 at 10 36 35 AM](https://github.com/zkluuke/Inspiron-3481-OpenCore-EFI/assets/111476831/9be6047a-add7-4461-afa8-281f44c4d60d)


> ### Notebook Specs
(*: components for this EFI work like expected)
- [x] <b>Model</b>: Dell Inspiron 14 3481
- [x] <b>CPU</b>: Intel Core i3 8130U @ 3.40GHz **Kaby Lake** *
- [x] <b>iGPU</b>: Intel UHD Graphics 620 *
- [x] <b>RAM</b>: 16GB DDR4 2666Mhz
- [x] <b>Storage</b>: 512GB Western Digital SSD
- [x] <b>Audio</b>: Realtek ALC256 HD Audio Controller *
- [x] <b>Wi-Fi</b>: Qualcomm QCA9377 Wireless Adapter (Doesn't work)
- [x] <b>Bluetooth</b>: Qualcomm QCA9377 Bluetooth *
- [x] <b>Ethernet</b>: Realtek RTL8139/810x Fast Ethernet Adapter *
- [x] <b>Display</b>: 1366x768 / 60 Hz

<details>
<summary><strong> Not Working </strong></summary>
<br>
| Wi-Fi   
| Internal Screen Brightness   
| Bluetooth

</details>

<details>
<summary><strong> Problems </strong></summary>
<br>

- Bluetooth doesn't work on macOS Ventura and Sonoma
- Wake from sleep only works sometimes and doesn't work on HDMI at all

</details>

> ### Notes
**Don't forget to generate your own SMBIOS using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)!**

HDMI and GPU as normal - HDMI is working and GPU has acceleration.   

USB ports are already mapped, if it doesn't work as expected, map it yourself [using this app](https://github.com/USBToolBox/tool) and change the "UTBMap.kext" kext.    

HideAuxiliary is **ON**

<details>
<summary><strong> Credits </strong></summary>
<br>

- [alkindivv](https://github.com//alkindivv/DELL-3421-BigSur) for the readme.
- [Acidanthera](https://github.com/acidanthera) for all the resources that made this possible.
- [Dortania](https://github.com/dortania) for for the OpenCore Install Guide.

</details>
