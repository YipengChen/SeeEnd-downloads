# 下载 SeeEnd

> 本目录主下载入口保留 `release-status.json` 中最后留存的已发布 0.8.6 记录，本轮未联网复核。App 0.8.55／扩展 0.2.12 的本地材料在 releases/v0.8.55/ 准备；隐私页面源文稿已审校并纳入本次仓库更新，公开部署以 GitHub Pages 实际状态为准。

**[下载 SeeEnd 0.8.6 · macOS Apple 芯片](https://github.com/YipengChen/SeeEnd-downloads/releases/download/v0.8.6/SeeEnd-0.8.6-Darwin-arm64.zip)**

**只需下载此安装包。** 已包含 App 和运行依赖，解压后启动 SeeEnd.app 即可。没有灯具也能使用。

[安装与帮助](https://yipengchen.github.io/SeeEnd-downloads/support.html) · [版本说明](https://github.com/YipengChen/SeeEnd-downloads/releases/tag/v0.8.6) · [隐私政策](https://yipengchen.github.io/SeeEnd-downloads/)

当前为桌面预览版，仅支持 macOS Apple 芯片，使用 ad-hoc 签名，尚未经过 Apple 公证。

<details>
<summary>第三方源码与许可材料（可选，使用 App 无需下载）</summary>

安装包已包含 Qt、PySide6 等运行依赖及许可文本。下列材料仅供查阅、修改或重新构建第三方库时使用。

[按需下载第三方源码与构建材料](https://github.com/YipengChen/SeeEnd-downloads/releases/download/v0.8.6/SeeEnd-third-party-sources-0.8.6.zip)

第三方材料保留各自许可，不包含 SeeEnd 原创源码。GitHub 自动生成的 Source code 档案仅包含本公开仓库的文档，也无需下载即可使用 App。

[第三方许可说明](THIRD_PARTY_NOTICES.md) · [动态库替换说明](LIBRARY_REPLACEMENT.md)

第三方材料 SHA-256：`92eb0f90b4d084afff977d90f68448649306f7ea97a873caebe4397a3d47fc5a`

</details>

<details>
<summary>安装包校验与技术说明</summary>

`SeeEnd-0.8.6-Darwin-arm64.zip` SHA-256：`d9716d9d53eca7b826a6b93405c4f284e2b2689df0d27327f521007215d9cff6`

22 个核心模块编译为原生机器码，安装包不携带这些模块的 Python 源码或字节码。原生编译提高逆向成本，不保证无法逆向；界面、接入适配器和随包 JavaScript 不在核心编译范围内。

[详细测试说明](releases/v0.8.6/TESTING.md) · [构建身份与完整资产清单](releases/v0.8.6/release.json)

</details>

<details>
<summary>浏览器扩展与编程工具 Skill</summary>

安装包内已包含浏览器扩展；通常按 App 的「安装浏览器扩展」教程操作即可，无需单独下载。

[开发扩展 0.2.10 ZIP](https://github.com/YipengChen/SeeEnd-downloads/releases/download/v0.8.6/SeeEnd-Web-extension-0.2.10.zip) · [SeeEnd Skill 1.0.1](https://github.com/YipengChen/SeeEnd-skill/releases/tag/v1.0.1)

商店格式的扩展 ZIP 为待提交材料，GitHub 上传不表示 Chrome 商店提交或审核通过。

</details>

发布者：Yipeng Chen · 联系邮箱：ypchenmail@gmail.com

SeeEnd 原创代码从 0.8.4 起采用[专有许可](LICENSE)，源码仓库保持私有。本公开仓库仅提供安装包、政策、安装说明和许可材料，不含 SeeEnd 原创源码。

[0.8.6 发布资料](releases/v0.8.6/README.md) · [历史 0.8.5](https://github.com/YipengChen/SeeEnd-downloads/releases/tag/v0.8.5)
