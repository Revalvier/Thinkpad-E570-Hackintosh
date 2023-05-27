<!-- omit in toc -->
#  macOS on Lenovo E570

OpenCore config for Hackintosh OpenCore Lenovo E570.

[![macOS](https://img.shields.io/badge/macos-13.4-green)](https://www.apple.com/macos/ventura/)
[![OpenCore](https://img.shields.io/badge/opencore-0.9.2-green)](https://github.com/acidanthera/OpenCorePkg)
[![release](https://img.shields.io/badge/download-latest%20version-blue.svg)](https://github.com/Revalvier/Thinkpad-E570-Hackintosh/releases/)

## Screenshot
<details>
<summary>macOS Ventura Beta 6</summary>

![](https://upload.wikimedia.org/wikipedia/en/7/70/MacOS_Ventura_Desktop.png)

</details>

<!-- omit in toc -->
## Hardware

| **LENOVO** | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Model Name      | Lenovo E570      |
| CPU              | Intel(R) Core(TM) i5-7200U CPU @ 2.40GHz Kaby Lake             |
| RAM           | 8 GB 2400 MHz DDR4    |
| Graphic Card | Intel(R) HD Graphics 620 (1 GB)                     |
| Wi-Fi             | QCA9377 (non-functional, uses HoRNDIS by Joshua Wise) |
| Audio       | Conexant CX20753/4                       |


## What are working (Almost Everything)

| **Details**                                |                                    |
| -----------------------------------  | -------- |
|  Turbo boost and CPU frequency stage |  ✅  |
|  Intel UHD Graphics 620              |  ✅  |
|  Brightness control                  |  ✅  |
|  HDMI                                |  ✅  |
|  Audio Conexant CX20753/4 layout-id: `15` |  ✅  |
|  Realtek Ethernet RTL8111            |  ✅  | 
|  iMessage         |  ✅  |
|  USB 3.0 and Type-C (with Port Map        |  ✅  |
|  Touchpad (14 gestures are working)   |  ✅  |
|  Battery status   |  ✅  |
|  S3 Sleep / Wake   |  ✅  |
|  S4 Hibernation / Wake   |  ✅  |
|  Camera   |  ✅  |
|  Fn shortcut keys   |  ✅  |
 

## What You Have to Do

- SMBIOS Settings


Thanks to relaxewdy for making the custom DSDT patches.
