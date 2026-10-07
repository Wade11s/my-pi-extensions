<div align="center">

# my-pi-extensions

**我维护的 pi 插件 —— 以及我推荐的第三方插件。**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![Pi packages](https://img.shields.io/badge/Pi-package%20gallery-111111.svg)](https://pi.dev/packages)

[English](./README.md) | 简体中文

</div>

---

面向 [pi coding agent](https://github.com/earendil-works/pi) 的插件精选索引。插件源码
各自独立成库，本仓库只维护这份 README。

## 我的插件

| 插件 | 状态 | 分类 | 能力 |
| --- | --- | --- | --- |
| [pi-speed](https://github.com/Wade11s/pi-speed) | 🚀 持续优化 | 状态栏指标 | 在 pi 原生界面中实时显示首字延迟、生成速度与会话累计时长。 |
| [pi-x-search](https://github.com/Wade11s/pi-x-search) | 🚀 持续优化 | X 搜索 | 让 Agent 通过官方 xAI 接口检索公开 X/Twitter 内容。 |
| [pi-explain](https://github.com/Wade11s/pi-explain) | 🚧 开发中 | 内容生成 | 把一次解释输出为清晰文字、静态图解或可交互网页。 |
| [pi-stepfun](https://github.com/Wade11s/pi-stepfun) | 🔧 维护 | 模型 Provider | 在 pi 中接入阶跃星辰 Step Plan 订阅套餐模型。 |
| [pi-radeon-cloud-cn](https://github.com/Wade11s/pi-radeon-cloud-cn) | 🔧 维护 | 模型 Provider | 为 pi 添加 AMD Radeon Cloud CN 模型服务。 |
| [pi-web-toolkit](https://github.com/Wade11s/pi-web-toolkit) | ⚠️ 已弃用 | 网页搜索与抓取 | 一套本地优先的网页研究工具集，可搜索、批量抓取并交互式浏览页面。 |

多数插件需要 **Node.js ≥ 22.19**。安装或更新后在已打开的会话里执行 `/reload`，或重启 pi。

## 安装与包管理

```bash
pi install npm:pi-web-toolkit              # 从 npm 安装
pi install git:github.com/Wade11s/pi-speed # 从 git 仓库安装
pi install -l npm:pi-stepfun               # 项目级安装（写入 .pi/settings.json）
pi -e npm:pi-stepfun                       # 仅本次试用，不写入配置

pi list                                    # 列出已安装包
pi update npm:pi-stepfun                   # 更新
pi remove npm:pi-stepfun                   # 卸载
```

## 参与贡献

Issue 与 PR 请提到各个插件自己的仓库，而不是本仓库。本仓库只维护这份 README。

## 许可证

[MIT](./LICENSE) © 2026 Wade Huang
