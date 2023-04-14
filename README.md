## Lenovo Thinkpad L480 Hackintosh Using Opencore
![Lenovo Thinkpad L480 Ventura](https://i.imgur.com/noEfWSz.png)

## Installation Guide Followed
 OpenCore Install Guide https://dortania.github.io/OpenCore-Install-Guide/
 
## IMP FOR BOOTING
 You will Need to gen serial and add it to config.plist using Gensmbios

## System Configuration
Lenovo Thinkpad L480
- Audio Device ALC257
- Intel i5 8250U - Whiskey Lake
- Intel UHD 620 (iGPU)
- Intel Ac-8265 Wifi/Bluetooth Card
## What is working
- Intel UHD 620 Graphics
- Type C Display Out Works
- Brightness Control
- HDMI
- Camera
- Battery Status
- LAN
- WiFi
- BlueTooth
- USB Controller
- System Trackpad and keyboard
- External USB Keyboard and Mouse
- Sleep Works
- Audio Working 

## Troubleshooting
### MacOS Installer (Recovery) not showing up in OpenCore
If OpenCore does not show you the MacOS installer (recovery) inside the boot picker. Set `HideAuxiliary` inside your config.plist to `true`.

## References & Special thanks to
- [OpenCore](https://dortania.github.io/OpenCore-Install-Guide/)
- [gibMacOS ](https://github.com/corpnewt/gibMacOS)
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
