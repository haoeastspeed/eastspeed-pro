# 东方神速 Pro（East Speed Pro）— 授权版发布仓库

本仓库托管东方神速 **Pro 授权版（formal 变体）** 的 Release 成品与自动更新清单，不存放源码（源码统一在私有 east-speed 仓库）。本仓库与免费试用版仓库 [haoeastspeed/eastspeed](https://github.com/haoeastspeed/eastspeed) **功能完全一致**，区别仅在于授权形态。

## 版本说明（两个版本）

| | Pro 授权版（本仓库） | 免费试用版 |
|---|---|---|
| 仓库 | haoeastspeed/eastspeed-pro | haoeastspeed/eastspeed |
| 授权 | 需激活授权，**无试用期** | 免费，自首次启动起 1 年内全功能无限制 |
| 启动 | 需在线/离线激活后进入主程序 | 直接使用，无授权入口 |
| 适用人群 | 付费用户 / 内部使用 | 个人用户、免费分享 |

- 个人用户推荐使用免费的 [试用版](https://github.com/haoeastspeed/eastspeed)。
- 本 Pro 版安装后需使用授权码激活；未激活无法进入主程序。

## 下载

在 [Releases](https://github.com/haoeastspeed/eastspeed-pro/releases/latest) 中选择：

- **East-Speed-Pro.exe**：单文件可执行版（开箱即用，推荐）
- **East-Speed-Pro-Setup.exe**：标准安装版
- **East-Speed-Pro-MSI.msi**：MSI 安装包，支持静默安装、可封装进系统镜像
- **East-Speed-Pro-Portable.zip**：免安装便携版

### 国内下载加速

GitHub 直连国内较慢且波动，可按以下顺序选择（文件内容完全一致）：

1. **官方边缘镜像（推荐，稳定、支持多线程/断点续传）**，例如单文件版：
   - https://update.eastspeed.dpdns.org/pro/East-Speed-Pro.exe
   - 安装版：https://update.eastspeed.dpdns.org/pro/East-Speed-Pro-Setup.exe
2. **第三方 GitHub 加速（公益服务，可能限流或关停；若失效请改用上面的官方镜像或 GitHub 直连）**：
   - https://gh-proxy.com/https://github.com/haoeastspeed/eastspeed-pro/releases/latest/download/East-Speed-Pro.exe

## 自动更新与激活

- 更新清单：`latest-formal.json`（Ed25519 签名，channel=formal）。
- 国内以 Cloudflare 边缘节点为主：`https://update.eastspeed.dpdns.org/latest-formal.json`，多线程下载，GitHub 直连自动备用，支持断点续传（Range/206）。
- 激活支持**在线激活**（优先）与**离线激活**两种方式，激活窗口内可切换。

## 版权

Copyright © 2026 郝东方（Hao Dongfang）. 保留所有权利。

未经书面许可，不得复制、修改、反编译、反向工程或重新分发本软件的任何部分。
