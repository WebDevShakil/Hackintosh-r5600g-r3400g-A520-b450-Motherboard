Hackintosh Project Overview
This project aims to create a Hackintosh using Ryzen APUs, specifically:

Supported Processors:

Ryzen 5600G
Ryzen 2400G
Ryzen 3400G
Supported Motherboards:

MSI, Gigabyte, or Asus
A320M, A440M, A520M, B450M
Graphics Support:

Utilize integrated graphics from the Ryzen APUs.
Use Lilu and WhateverGreen for better graphics support.
Networking:

Support for Ethernet and specific Wi-Fi modules.
Use of the Wireless USB Adapter for compatibility.
Mobile USB Wi-Fi support through Hornet.
EFI Folder Support
Make sure your EFI folder contains the necessary drivers and configurations for your hardware. Here's a basic outline of what you might need:

EFI/CLOVER or EFI/OC: Depending on whether you're using Clover or OpenCore.

Drivers: Essential drivers for booting, like HFSPlus.efi, OpenRuntime.efi, etc.

Kexts:

Lilu.kext
WhateverGreen.kext
VirtualSMC.kext
Any additional kexts specific to your hardware (e.g., Ethernet or USB support).
Config.plist: Ensure your config file is tailored to your specific hardware, including:

CPU settings
Boot arguments
Device properties for graphics and networking.
Disclaimer
Remember, this project is strictly for educational purposes and experimentation, as installing macOS on non-Apple hardware violates Apple's End User License Agreement. Be sure to back up your data and proceed with caution!

If you need help with specific issues or configurations, feel free to ask!



