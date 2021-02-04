# Hackintosh Big Sur Installation Guide

Thanks @czombos for BIOS setup images and some ideas I used here!

Perfect Vanilla Hackintosh with OpenCore bootloader like real Mac.

OpenCore supports boot hotkeys, hold Option or ESC at startup to choose a boot device, Command+R to enter Recovery or Command+Option+P+R to reset NVRAM.

I used this guides as starting point:

https://github.com/dortania/OpenCore-Desktop-Guide

https://github.com/acidanthera/OpenCorePkg/blob/master/Docs/Configuration.pdf

## Hardware

- 1 x Case: NCase M1 V6.1 Black (Hania)
- 1 x Motherboard: Asus ROG Strix Z390-I Gaming M-ITX (Marta)
- 1 x Central Processor Unit: Intel Core i9-9900K, 3.6GHz, 16 MB, BOX (Monika)
- 1 x Central Processor Unit Cooling AIO: Asus ROG Strix LC 240 AiO CPU Cooler with Aura Sync RGB (Oliwia)
- 1 x Random Access Memory: Corsair Vengeance LPX DDR4 64GB 3200MHz CL16 (Ola i Zosia)
- 1 x Solid State Drive for OS: Western Digital SSD 2TB SN750 NVMe (Magda)
- 1 x Graphic Processor Unit: XFX AMD Radeon VII 16GB HBM2 (Renata)
- 1 x Power Supply: Corsair SF Series SF750 750W 80 PLUS Platinum SFX (Lucja)
- 1 x BCM94352Z/DW1560 for WiFi and Bluetooth (native replacement on motherboard) (Justyna)
- 1 x Operating System: macOS Big Sur 11.2

## What works

- Sleep / Wake
- Power Nap (sleep with background operations such as Time Machine)
- Audio
- Ethernet
- Bluetooth
- Wi-Fi
- 15 USB ports
- AMD DRM for Music, Safari, TV, Plex, Prime, IQSV

## My Workstation

https://iblog.isowa.io/2020/03/02/hania-pc-well-it-needs-macos/

## macOS System Information

<details>

## USBMap

Selected XHC ports (max 15)

| Ports | Type | Description |
| --- | --- | --- |
| HS02 | USB 3 Type C connector | Rear USB Type-C |
| HS05 | USB 2 Type A connector | Rear USB 2.0 (black) |
| HS06 | USB 2 Type A connector | Rear USB 2.0 (black) |
| HS07 | USB 3 Standard-A connector | Rear USB 3.1 Gen 1 (blue) |
| HS08 | USB 3 Standard-A connector | Rear USB 3.1 Gen 1 (blue) |
| HS09 | USB 3 Standard-A connector | Front USB 3.1 Gen 1 |
| HS10 | USB 3 Standard-A connector | Front USB 3.1 Gen 1 |
| HS14 | Internal connector | Bluetooth/Wifi - BCM2045A0 |
| SS03 | USB 3 Standard-A connector | Rear USB 3.1 Gen 2 (red) |
| SS04 | USB 3 Standard-A connector | Rear USB 3.1 Gen 2 (red) |
| SS06 | USB 3 Type C connector | Rear USB Type-C |
| SS07 | USB 3 Standard-A connector | Rear USB 3.1 Gen 1 (blue) |
| SS08 | USB 3 Standard-A connector | Rear USB 3.1 Gen 1 (blue) |
| SS09 | USB 3 Standard-A connector | Front USB 3.1 Gen 1 |
| SS10 | USB 3 Standard-A connector | Front USB 3.1 Gen 1 |
| PATCH | USB 3 Type C connector | Front USB Type-C |

## BIOS settings

<details>
<summary>Screenshots</summary>

![](IMAGES/bios/JPEG/191214130141.jpg)

![](IMAGES/bios/JPEG/191214125642.jpg)

![](IMAGES/bios/JPEG/191214125654.jpg)

![](IMAGES/bios/JPEG/191214125702.jpg)

![](IMAGES/bios/JPEG/191214125704.jpg)

![](IMAGES/bios/JPEG/191214125709.jpg)

![](IMAGES/bios/JPEG/191214125714.jpg)

![](IMAGES/bios/JPEG/191214125734.jpg)

![](IMAGES/bios/JPEG/191214125737.jpg)

![](IMAGES/bios/JPEG/191214125743.jpg)

![](IMAGES/bios/JPEG/191214125749.jpg)

![](IMAGES/bios/JPEG/191214125755.jpg)

![](IMAGES/bios/JPEG/191214125757.jpg)

![](IMAGES/bios/JPEG/191214125803.jpg)

![](IMAGES/bios/JPEG/191214125811.jpg)

![](IMAGES/bios/JPEG/191214125816.jpg)

![](IMAGES/bios/JPEG/191214125821.jpg)

![](IMAGES/bios/JPEG/191214125829.jpg)

![](IMAGES/bios/JPEG/191214125833.jpg)

![](IMAGES/bios/JPEG/191214125838.jpg)

![](IMAGES/bios/JPEG/191214125841.jpg)

![](IMAGES/bios/JPEG/191214125846.jpg)

![](IMAGES/bios/JPEG/191214125854.jpg)

![](IMAGES/bios/JPEG/191214125902.jpg)

![](IMAGES/bios/JPEG/191214125935.jpg)

![](IMAGES/bios/JPEG/191214125949.jpg)

![](IMAGES/bios/JPEG/191214125954.jpg)

![](IMAGES/bios/JPEG/191214125958.jpg)

![](IMAGES/bios/JPEG/191214130001.jpg)

</details>
