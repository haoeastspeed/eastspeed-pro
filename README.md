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

- **East Speed Pro Setup.exe**：标准安装版（推荐）
- **East Speed Pro MSI.msi**：MSI 安装包，支持静默安装、可封装进系统镜像
- **East Speed Pro Portable.zip**：免安装便携版
- **EastSpeedPro.exe**：单文件可执行版
- **East Speed LicenseTool.exe**：发码 / 授权管理工具（内部使用）

## 自动更新

- 更新清单：`latest-formal.json`（Ed25519 签名，channel=formal）
- 国内以 Cloudflare 边缘节点为主：`https://update.eastspeed.dpdns.org/latest-formal.json`，GitHub 直连自动备用，支持断点续传（Range/206）。

## 版权

Copyright © 2026 郝东方（Hao Dongfang）. 保留所有权利。

未经书面许可，不得复制、修改、反编译、反向工程或重新分发本软件的任何部分。
