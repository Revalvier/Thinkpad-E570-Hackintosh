<!-- omit in toc -->
#  macOS on Lenovo E570

OpenCore config for Hackintosh OpenCore Lenovo E570.

[![macOS](https://img.shields.io/badge/macos-12.0%20beta-yellowgreen)](https://www.apple.com/macos/monterey-preview/)
[![OpenCore](https://img.shields.io/badge/opencore-0.7.1-green)](https://github.com/acidanthera/OpenCorePkg)
[![release](https://img.shields.io/badge/download-lastest%20version-blue.svg)](https://github.com/Revalvier/Thinkpad-E570-Hackintosh/releases/)

## Screenshot
<details>
<summary>Big Sur</summary>

![](https://i.loli.net/2021/02/17/svA1zWm6CrGBDu3.png)

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
- Rename config


Thanks to relaxewdy for making the custom DSDT patches.
