**简体中文** | [English](#english)

# N32WB03x-SDK

> 当前导入版本：**v2.0.0**  
> 原始软件包目录：`N32WB03x_SDK_V2.0.0`

## 概述

**N32WB03x-SDK** 是 N32WB03x 系列微控制器的固件开发套件，由 Nsing-Community 社区维护。仓库保留固件库、示例工程及随原始软件包提供的中间件和工具。

## 目录

- `.git/`
- `firmware/`
- `middlewares/`
- `projects/`
- `utilities/`

## 使用方法

克隆仓库后，请根据目标评估板和工具链打开 `projects/`、`RVMDK/` 或相应工程目录中的 Keil MDK、IAR EWARM、GCC 工程。具体硬件连接和运行现象以各示例目录中的说明文件为准。

## 版本

版本历史请参阅 `release_notes.txt`。

## 安全与外部工具

- OTA/DFU 演示私钥未纳入仓库。使用前请运行 `utilities/dfu/GenerateKeyPair.bat` 生成自己的密钥，生产设备不得使用公开演示密钥。
- SEGGER J-Link 可执行文件未在本仓库中再分发，请从 SEGGER 官方渠道安装。

## 许可证与来源

代码版权及许可遵循各源文件头部声明；第三方中间件和工具遵循各自附带的许可证。本仓库是社区维护的开发资源镜像，不代表对第三方组件许可的替代或重新授权。

---

## <a name="english"></a>English

# N32WB03x-SDK

> Imported version: **v2.0.0**  
> Original package directory: `N32WB03x_SDK_V2.0.0`

## Overview

**N32WB03x-SDK** is the firmware development kit for the N32WB03x microcontroller family, maintained by Nsing-Community. It preserves the firmware libraries, example projects, middleware, and tools supplied with the source package.

## Top-level contents

- `.git/`
- `firmware/`
- `middlewares/`
- `projects/`
- `utilities/`

## Usage

Clone the repository, then open the appropriate Keil MDK, IAR EWARM, or GCC project under `projects/`, `RVMDK/`, or the relevant project directory. Refer to the documentation included with each example for board connections and expected behavior.

## Version

See `release_notes.txt` for the original version history.

## Security and external tools

- The OTA/DFU demo private key is intentionally excluded. Run `utilities/dfu/GenerateKeyPair.bat` to generate your own key, and never use a public demo key on production devices.
- SEGGER J-Link executables are not redistributed in this repository. Install J-Link from SEGGER's official distribution.

## License and provenance

Source files remain under the copyright and license notices in their headers. Third-party middleware and tools remain under their respective licenses. This repository is a community-maintained development-resource mirror and does not replace or relicense third-party terms.
