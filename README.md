# OpenCore EFI for ROG STRIX B550-I GAMING

![photo](https://github.com/viking76/hackintosh-rog-b550i/blob/master/Pictures/ventura.png?raw=true)

# Specification

| **Component** | **Model** |
| ------------- | --------- |
| CPU | AMD Ryzen 9 3900X @ 3.9GHz |
| Motherboard | ASUS Rog Strix B550i |
| RAM | 16B (2 x 8GB) 
| Audio Chipset | ALC-S1220A |
| GPU | SAPPHIRE NITRO+ RX 580 8G G5 |
| WiFi & Bluetooth | Intel® Wi-Fi 6 AX200 |
| Lan |  Intel® I225-V 2.5Gb Ethernet |
| OS Disk | Samsung 960 Evo 500GB |
| macOS |  13.3.1/ OpenCore 0.8.8

## What works
- Audio (`alcid=3`)
- Ethernet (with ACPI and kext)
- USB (USB mapping)
- Wi-Fi (Airportitlwm for ventura)
- Bluetooth
- iMessage, FaceTime

## Known issues
- not work Partially-working virtualization (only VirtualBox & Parallels Dekstop 13.1.0 or below)
- 3.5mm Jack microphone (haven't tested)

## Update
Simply use OCAuxiliaryTools package   https://github.com/ic005k/OCAuxiliaryTools

## Credits
- everyone developing for the hackintosh community and before me huuakhai that send his config.
- the [dortania team](https://github.com/orgs/dortania/people)
