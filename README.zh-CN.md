<a name="levin-harness"></a>
<h1 align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/wordmark-on-dark.png" />
    <source media="(prefers-color-scheme: light)" srcset="assets/wordmark-on-light.png" />
    <img src="assets/wordmark-on-light.png" width="320" alt="Levin Harness" />
  </picture>
</h1>

<p align="center"><strong>让科学发现可编程。</strong></p>

<p align="center">
  面向药物研发的 AI 智能体桌面工作区。<br />
  将模型、科学工具、分子结构与计算资源连接到同一个研究流程中。
</p>

<p align="center">
  <a href="README.md">English</a> | <strong>简体中文</strong>
</p>

<p align="center">
  <strong><a href="https://levinthal.design/public/downloads/Levin-Harness-2.902.4-arm64.dmg">下载 macOS 版</a></strong> ·
  <a href="https://levinthal.design/install.html">安装指南</a> ·
  <a href="https://levinthal.design/docs.html">使用文档</a> ·
  <a href="https://github.com/levinthal/levin-harrness/releases">版本发布</a> ·
  <a href="https://github.com/levinthal/levin-harrness/issues/new/choose">问题反馈</a>
</p>

<p align="center">预览版 · Apple silicon · 自备模型服务</p>

![Levin Harness 工作区：AI 智能体对话与 Mol* 中的 1AON 分子结构同屏显示](assets/workspace.webp)

这是 Levin Harness 的官方发布与反馈仓库，用于提供产品介绍、安装包和收集用户反馈。应用源码暂不公开。

## 下载

| 平台 | 下载 | 状态 |
| --- | --- | --- |
| macOS，Apple silicon | [Levin Harness 2.902.4（.dmg）](https://levinthal.design/public/downloads/Levin-Harness-2.902.4-arm64.dmg) | 预览版 |

当前安装包由官网提供。后续在此发布的安装包和版本说明可在 [Releases](https://github.com/levinthal/levin-harrness/releases) 查看。

请下载 `.dmg` 安装包。GitHub 的 **Code > Download ZIP** 和自动生成的 **Source code** 压缩包只包含本仓库的说明文档与图片，不包含应用程序。

## 在同一个工作区完成科研任务

| 核心能力 | 可以做什么 |
| --- | --- |
| [分子工作区](https://levinthal.design/molecular-workspace.html) | 在 Mol* 中查看和分析分子结构，让结构、序列与智能体对话保持关联。 |
| [科学插件](https://levinthal.design/plugins.html) | 配置 ProteinMPNN、FAMPNN、ThermoMPNN、RFantibody 等工具，从对话或工作流中调用，也可通过 Python Plugin SDK 扩展。 |
| [科研工作流](https://levinthal.design/workflows.html) | 与智能体在同一张可视化画布上构建、调整和复用研究流程。 |
| [远程 GPU](https://levinthal.design/remote-gpu.html) | 通过 SSH 连接自己的 Linux GPU 服务器，在远端执行受支持的插件与计算任务。 |
| [自选模型](https://levinthal.design/install.html) | 为任务配置模型供应商或兼容的服务地址，也可使用私有或自托管服务。 |

<details>
<summary>查看工作流画布</summary>

![Levin Harness 工作流画布：抗体设计流程与智能体对话同屏显示](assets/workflows.webp)

</details>

## 开始使用

1. **安装应用。** 下载并打开 `.dmg`，将 Levin Harness 拖入 **Applications（应用程序）**。
2. **连接模型。** 打开 **Settings > Model > New provider**，填写模型服务配置，执行 **Test Connection**，保存并设为默认模型。
3. **打开项目。** 选择本地文件夹，检查任务权限，然后开始对话。可以先让智能体列出项目文件或总结一份文档。

完整步骤见[安装指南](https://levinthal.design/install.html)。远程 GPU 是可选项。

## 常见问题

### 支持哪些平台？

当前预览版支持搭载 Apple silicon 的 macOS 设备，暂未提供 Intel Mac、Windows 或 Linux 桌面安装包。Linux GPU 服务器可作为远程计算设备连接。

### 是否免费？

预览阶段目前对非商业用途免费，具体以[服务条款](https://levinthal.design/terms.html)为准。模型供应商可能单独收取使用费用，这部分费用不包含在 Levin Harness 中。

### 数据存储在哪里？

项目、对话、设置与 API Key 默认保存在本机。执行任务时，相关内容会发送给你配置的模型服务商；远程任务也可能向所选计算设备传输必要的输入。详情见[隐私政策](https://levinthal.design/privacy.html)及模型供应商的相关设置。

### 这是开源项目吗？

Levin Harness 应用源码暂不公开。本仓库提供产品说明、版本下载与反馈入口。集成开源工具不代表应用本身开源，各工具适用各自的使用条款。

## 反馈与社区

- [报告问题或提出功能建议](https://github.com/levinthal/levin-harrness/issues/new/choose)，支持中文和英文。
- 使用交流与科研工作流讨论可加入 [Discord](https://discord.gg/yENT5KyBT) 或[飞书社区](https://applink.feishu.cn/client/chat/chatter/add_by_link?link_token=93blb389-88ea-4c04-a071-fbff366977ae&qr_code=true)。
- 反馈所需信息见[支持说明](SUPPORT.md#中文)。

[官网](https://levinthal.design/) · [使用文档](https://levinthal.design/docs.html) · [服务条款](https://levinthal.design/terms.html) · [隐私政策](https://levinthal.design/privacy.html)
