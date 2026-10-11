# 东方神速 Pro（East Speed Pro）

**v1.0.1 · 初版正式发布**

东方神速是一款简洁干净、快速轻巧的 Windows 多线程下载管理器。本仓库托管 **Pro 正式版（formal 变体）** 的 Release 成品与自动更新清单，不存放源码（源码统一在私有 east-speed 仓库）。

## 版本说明

| | Pro 正式版（本仓库） | 免费试用版 |
|---|---|---|
| 仓库 | haoeastspeed/eastspeed-pro | haoeastspeed/eastspeed |
| 授权 | 激活码授权，支持在线 / 离线激活 | 免费，首次启动起 1 年内全功能无限制 |
| 维护 | 持续功能更新与 BUG 修复 | 已冻结于 v1.0.1，不再更新 |
| 适用 | 付费用户 / 内部使用 | 个人用户、免费体验 |

- 想先免费体验的个人用户，可使用 [试用版仓库](https://github.com/haoeastspeed/eastspeed)（已冻结于初版）。
- Pro 正式版安装后需使用授权码激活，激活支持**在线激活（优先）**与**离线激活**两种方式，激活窗口内可切换。

## 下载

在 [Releases](https://github.com/haoeastspeed/eastspeed-pro/releases/latest) 中选择：

- **EastSpeedPro.exe**：单文件可执行版（开箱即用，推荐）
- **EastSpeedProSetup.exe**：标准安装版
- **EastSpeedProMSI.msi**：MSI 安装包，支持静默安装、可封装进系统镜像
- **EastSpeedProPortable.zip**：免安装便携版

### 国内下载加速

GitHub 直连国内较慢且波动，可按以下顺序选择（文件内容完全一致），以单文件版为例：

1. **官方边缘镜像（推荐，稳定、支持多线程 / 断点续传）**：
   - 单文件：https://update.eastspeed.dpdns.org/pro/EastSpeedPro.exe
   - 安装版：https://update.eastspeed.dpdns.org/pro/EastSpeedProSetup.exe
   - 其他形态将文件名替换为 `EastSpeedProMSI.msi` 或 `EastSpeedProPortable.zip` 即可。
2. **第三方 GitHub 加速（公益服务，可能限流或关停；失效请改用官方镜像或 GitHub 直连）**：
   - https://gh-proxy.com/https://github.com/haoeastspeed/eastspeed-pro/releases/latest/download/EastSpeedPro.exe

## 主要功能

- 多线程分段下载，并发数可调（默认 16、最高 64），断点续传、失败自动重试、卡死连接自动切换。
- 智能分片：运行时动态分裂最慢分片、新连接接管以消除长尾；模拟真实浏览器指纹，通过防盗链与反爬校验。
- Edge / Chrome 配套扩展，一键接管网页下载。
- 网页媒体下载：m3u8(HLS) / DASH / mp4 / mp3 嗅探，自动下载分片并合并封装。
- 网盘直链：阿里云盘、夸克 / UC、123 等分享链接解析直连下载（可在设置中开关，阿里云盘可按需登录）。
- HTTP/HTTPS/FTP/SFTP、BT 种子与磁力、ed2k、哈希校验、计划队列、资源搜索、手机远程、代理与杀毒调用。

## 自动更新与激活

- 更新清单：`latest-formal.json`（Ed25519 签名，channel=formal）。
- 国内以 Cloudflare 边缘节点为主：https://update.eastspeed.dpdns.org/pro/latest-formal.json ，多线程下载，GitHub 直连自动备用，支持断点续传（Range/206）。
- 激活支持**在线激活（优先）**与**离线激活**，激活窗口内可切换。

## 版权

Copyright © 2026 郝东方（Hao Dongfang）. 保留所有权利。

未经书面许可，不得复制、修改、反编译、反向工程或重新分发本软件的任何部分。
