# 下载 SeeEnd

> 当前发布基线：App **0.8.56** / 浏览器扩展 **0.2.13** / Skill **1.0.3**。分发包已发布并完成匿名下载及 SHA-256 校验，详情见版本清单。扩展 0.2.13 已上传，后台现为待审核；当前商店已发布版本为 0.2.12。

本地已准备 App 0.8.68 / 扩展 0.2.14 / Skill 1.0.5 的修复版本，尚未公开发布；进度与资产见[本地准备清单](releases/v0.8.68/release.json)。

**[下载 SeeEnd 0.8.56 · macOS Apple 芯片](https://github.com/YipengChen/SeeEnd-downloads/releases/download/v0.8.56/SeeEnd-0.8.56-Darwin-arm64.zip)**

**只需下载此安装包。** 已包含 App 和运行依赖，解压后启动 SeeEnd.app 即可。没有灯具也能使用。

[安装与帮助](https://yipengchen.github.io/SeeEnd-downloads/support.html) · [版本说明](https://github.com/YipengChen/SeeEnd-downloads/releases/tag/v0.8.56) · [隐私政策](https://yipengchen.github.io/SeeEnd-downloads/)

当前为桌面预览版，仅支持 macOS Apple 芯片，使用 ad-hoc 签名，尚未经过 Apple 公证。

<details>
<summary>第三方源码与许可材料（可选，使用 App 无需下载）</summary>

安装包已包含 Qt、PySide6 等运行依赖及许可文本。下列材料仅供查阅、修改或重新构建第三方库时使用。

[按需下载第三方源码与构建材料](https://github.com/YipengChen/SeeEnd-downloads/releases/download/v0.8.56/SeeEnd-third-party-sources-0.8.56.zip)

第三方材料保留各自许可，不包含 SeeEnd 原创源码。GitHub 自动生成的 Source code 档案仅包含本公开仓库的文档，也无需下载即可使用 App。

[第三方许可说明](THIRD_PARTY_NOTICES.md) · [动态库替换说明](LIBRARY_REPLACEMENT.md)

第三方材料 SHA-256：`02cb60ea55946965585a93ea5fd1b2d824b15bddc00303c47ea1c039cd9778f9`

</details>

<details>
<summary>安装包校验与技术说明</summary>

`SeeEnd-0.8.56-Darwin-arm64.zip` SHA-256：`638154e7a56b601b66000e12c45934b06565dac588b41bfad31bfe7d84e1abae`

34 个核心模块编译为原生机器码，安装包不携带这些模块的 Python 源码或字节码。原生编译提高逆向成本，不保证无法逆向；界面、接入适配器和随包 JavaScript 不在核心编译范围内。

[详细测试说明](releases/v0.8.56/TESTING.md) · [构建身份与完整资产清单](releases/v0.8.56/release.json)

</details>

<details>
<summary>浏览器扩展与编程工具 Skill</summary>

安装包内已包含浏览器扩展；通常按 App 的「安装浏览器扩展」教程操作即可，无需单独下载。

[开发扩展 0.2.13 ZIP](https://github.com/YipengChen/SeeEnd-downloads/releases/download/v0.8.56/SeeEnd-Web-extension-0.2.13.zip) · [SeeEnd Skill 1.0.3](https://github.com/YipengChen/SeeEnd-skill/releases/tag/v1.0.3)

商店格式的扩展 ZIP 供分发核对；后台当前为 0.2.13 待审核，GitHub 发布不表示商店审核通过。

</details>

发布者：Yipeng Chen · 联系邮箱：ypchenmail@gmail.com

SeeEnd 原创代码从 0.8.4 起采用[专有许可](LICENSE)，源码仓库保持私有。本公开仓库仅提供安装包、政策、安装说明和许可材料，不含 SeeEnd 原创源码。

[0.8.56 发布资料](releases/v0.8.56/README.md) · [历史 0.8.6](https://github.com/YipengChen/SeeEnd-downloads/releases/tag/v0.8.6) · [历史 0.8.5](https://github.com/YipengChen/SeeEnd-downloads/releases/tag/v0.8.5)
