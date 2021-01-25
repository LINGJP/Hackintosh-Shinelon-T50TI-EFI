   中文 README 请看 [README_CN.md](README_CN.md)

## Configuration

| Model     | Shinelon T50TI/MacBookPro14,1    | Version        | 11.1                |
| :-------- | :--------------------------- | :------------- | :------------------ |
| Processor | Intel Core i5-7300HQ/i7-7700HQ | Graphics       | HD Graphics 630    |
| Memory    | Crucial 2400MHz DDR4 8GB  | Storage        | WD SN750 512GB |
| Audio     | Realtek ALC269               | WiFi/Bluetooth | Intel Wireless AC-3165   |
| Display   | NT156FHM-N41 1080P@60HZ            | Monitor        | NE156QUM-N66 4K@60HZ  |

### Not Working

- DiscreteGPU
- Unable to sleep

## Installation

**Please use [the latest release](https://github.com/LINGJP/Hackintosh-Shinelon-T50TI-EFI/releases/latest).** 

### Intel Wireless Card

This config supports Intel Wireless Card, but the default `AirportItlwm.kext` is for **BigSur**, if you are running other versions of macOS, you have to replace the default one from [OpenIntelWireless/itlwm](https://github.com/OpenIntelWireless/itlwm/releases).

### Big Sur

**For 4k display user**: You need to follow [the tutorial]（ https://lonelyqc.top/Hackintosh/T50TI.html ）Complete the modification of BIOS, including unlocking CFG lock and modifying DVMT to the maximum,WhateverGreen with commit [978cb8](https://github.com/acidanthera/WhateverGreen/commit/978cb8c7a744ac189074225fd8eb2f16feb5a4c0) can make panel running at 60Hz, **you no longer need the 48Hz patch**. Please choose config-4K.plist and perfect to use.

### Tap Delay

- Turn off `Enable dragging` or use `three finger drag` to avoid one-finger tap delay.
- Turn off `Smart zoom` to avoid two-finger tap delay.

See [is-it-possible-to-get-rid-of-the-delay-between-right-clicking-and-seeing-the-context-menu](https://apple.stackexchange.com/a/218181)
