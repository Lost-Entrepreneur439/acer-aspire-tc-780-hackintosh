# acer-aspire-tc-780-hackintosh-ventura
 A prebuilt OpenCore EFI for macOS Ventura on the Acer Aspire TC-780

**WARNING! Ethernet IS required for initial half of setup if you use an internet-based installer. You will need to install Heliport for Wi-Fi.

This is a macOS Ventura EFI for the Acer Aspire TC-780, with support for Intel Wi-Fi cards. 13.3.1a working, with OpenCore 0.9.1 and fully up to date kexts. Remember to keep your kexts and OpenCore up to date! I recommend OCAuxiliaryTools to keep your kexts and OpenCore up to date. Remember to change your SMBIOS data too.

![Screenshot](https://github.com/Lost-Entrepreneur439/acer-aspire-tc-780-hackintosh-ventura/blob/main/psrklly684wa1.png)

# Specs of my specific unit:

* CPU: Intel Core i3-7100
* GPU: Intel HD Graphics 630
* RAM: 8GB Micron DDR4
* Model: Acer Aspire TC-780-AM11
* Audio: Realtek ALC662
* Ethernet: Realtek RTL8168/8111
* Wifi/Bluetooth: Intel Dual Band Wireless-AC 3168

Follow the "Downloading macOS section in the Dortania guide to get macOS. **Support will not be offered if you get macOS from any other source.** https://dortania.github.io/OpenCore-Install-Guide/installer-guide/windows-install.html#downloading-macos

# Set BIOS settings as follows

* Authentication -> Secure Boot -> Disabled
* Boot Options -> Launch CSM -> Never

# Credits

* [Acidanthera](https://github.com/acidanthera) -- Made OpenCore, AppleALC, BlueToolFixup, Lilu, VirtualSMC and WhateverGreen
* [OpenIntelWireless](https://github.com/OpenIntelWireless) -- Made itlwm
* [FireWolf](https://github.com/0xFireWolf) -- Made RealtekCardReader
* [Laura Müller](https://github.com/Mieze) -- Made RealtekRTL8111 
* [USBToolBox](https://github.com/USBToolBox) -- Made USBToolBox
* [Apple](https://www.apple.com/ca/) -- Made macOS
* [Acer](https://www.acer.com/us-en) -- Made the Aspire TC-780
* [Dortania](https://github.com/dortania) -- Made the OpenCore install guide which was used to make this EFI
* [CorpNewt](https://github.com/corpnewt) -- Helped me fix graphics
