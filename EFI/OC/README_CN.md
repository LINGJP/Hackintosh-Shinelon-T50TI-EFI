## 配置

| 型号   | Shinelon T50TI/MacBookPro14,1 | 版本   |       11.1          |
| :----- | :--------------------------- | :----- | :------------------ |
| 处理器 | Intel Core i5-7300HQ/i7-7700HQ | 图形   | HD Graphics 630    |
| 内存   | Micron 2400MHz DDR4 8GB x2   | 硬盘   | WD SN750 512GB       |
| 声卡   | Realtek ALC298               | 网卡   | Intel Wireless AC-3165 |
| 内屏   | NT156FHM-N41 1080P@60HZ      | 显示器 | NE156QUM-N66 4K@60HZ  |

### 不工作的设备

- 独立显卡
- 无法睡眠

## 安装

**请下载 [最新的 release](https://github.com/LINGJP/Hackintosh-Shinelon-T50TI-EFI/releases/latest)**。

### Intel 网卡

默认的 `AirportItlwm.kext` 是用于 Catalina 的，如果你在使用 Big Sur 或者其他版本的系统，请到 [OpenIntelWireless/itlwm](https://github.com/OpenIntelWireless/itlwm/releases) 下载并替换，你也可以换成 `itlwm.kext + HeliPort.app`，别忘了更新 config.plist。

### Big Sur

**对于 4K 内屏用户**，WhateverGreen [978cb8](https://github.com/acidanthera/WhateverGreen/commit/978cb8c7a744ac189074225fd8eb2f16feb5a4c0)  能让内屏运行于 60Hz 了，不再需要 48Hz 补丁，请选择config-4K.plist以便更好的使用。

### CLOVER 主题

可以使用如下执行设置 CLOVER 的主题为 [themes](https://sourceforge.net/p/cloverefiboot/themes/ci/master/tree/themes/) 中的某个主题（xxx 为主题名）

### 触摸板单双击延迟

- 关闭拖拽或者使用三指拖拽可以避免单击的延迟
- 关闭智能缩放可以避免双击的延迟