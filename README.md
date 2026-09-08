<a name="levin-harness"></a>
<h1 align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/wordmark-on-dark.png?v=2" />
    <source media="(prefers-color-scheme: light)" srcset="assets/wordmark-on-light.png?v=2" />
    <img src="assets/wordmark-on-light.png?v=2" width="320" alt="Lévin™ Harness" />
  </picture>
</h1>

<p align="center"><strong>Make scientific discovery programmable.</strong></p>

<p align="center">
  An AI agent desktop workspace for drug discovery.<br />
  Connect models, scientific tools, molecular structures, and compute in one research workflow.
</p>

<p align="center">
  <strong>English</strong> | <a href="README.zh-CN.md">简体中文</a>
</p>

<p align="center">
  <strong><a href="https://github.com/levinthal/levin-harrness/releases">Download for macOS</a></strong> ·
  <a href="https://levinthal.design/install.html">Installation</a> ·
  <a href="https://levinthal.design/docs.html">Documentation</a> ·
  <a href="https://github.com/levinthal/levin-harrness/releases">Releases</a> ·
  <a href="https://github.com/levinthal/levin-harrness/issues/new/choose">Feedback</a>
</p>

<p align="center">Preview · Apple silicon · Bring your own model</p>

![Lévin™ Harness workspace with an AI agent conversation and the 1AON molecular structure in the Mol* viewer](assets/workspace.webp)

This is the official repository for Lévin™ Harness releases, product information, and user feedback. The application source code is not publicly available.

## Download

| Platform | Download | Status |
| --- | --- | --- |
| macOS, Apple silicon | [Download from Releases](https://github.com/levinthal/levin-harrness/releases) | Preview |

Choose a version in [Releases](https://github.com/levinthal/levin-harrness/releases), review its release notes, and download the `.dmg` installer from **Assets**.

GitHub's **Code > Download ZIP** and automatically generated **Source code** archives contain this repository's documentation and images, not the application.

## One workspace for scientific work

| Capability | What you can do |
| --- | --- |
| [Molecular workspace](https://levinthal.design/molecular-workspace.html) | Inspect molecular structures in Mol* while keeping the structure, sequence, and agent conversation together. |
| [Scientific plugins](https://levinthal.design/plugins.html) | Set up tools such as ProteinMPNN, FAMPNN, ThermoMPNN, and RFantibody, then call them from a chat or workflow. Extend the catalog with the Python Plugin SDK. |
| [Research workflows](https://levinthal.design/workflows.html) | Build and refine reusable research processes with the agent on a shared visual canvas. |
| [Remote GPU](https://levinthal.design/remote-gpu.html) | Connect your own Linux GPU host over SSH and run supported plugins and compute tasks remotely. |
| [Your choice of model](https://levinthal.design/install.html) | Configure a model provider or compatible endpoint for your tasks, including private or self-hosted services. |

<details>
<summary>See the workflow canvas</summary>

![Lévin™ Harness showing an antibody design workflow on a visual canvas alongside an agent conversation](assets/workflows.webp)

</details>

## Get started

1. **Install the app.** Download the `.dmg`, open it, and drag Lévin™ Harness into **Applications**.
2. **Connect a model.** Open **Settings > Model > New provider**, enter your provider configuration, run **Test Connection**, and save it as the default model.
3. **Open a project.** Choose a local folder, review the task permissions, and start a conversation. Try asking the agent to list the project files or summarize a document.

See the [installation guide](https://levinthal.design/install.html) for the complete setup. A remote GPU is optional.

## FAQ

### Which platforms are supported?

The current preview supports macOS on Apple silicon. Builds for Intel Macs, Windows, and Linux are not currently available. A Linux GPU machine can be connected as a remote compute host.

### Is Lévin™ Harness free?

The preview is currently free for non-commercial use, subject to the [Terms of Service](https://levinthal.design/terms.html). Model providers may charge separately for usage; those fees are not included with Lévin™ Harness.

### Where does my data go?

Projects, conversations, settings, and API keys are stored locally by default. Task content is sent to the model provider you configure, and remote tasks may transfer the inputs needed by your chosen compute host. Review the [Privacy Policy](https://levinthal.design/privacy.html) and your provider's settings for details.

### Is this an open-source project?

The Lévin™ Harness application source code is not public. This repository provides product information, release downloads, and a place to report problems or request features. Using an integrated open-source tool does not make the application itself open source; individual tools have their own terms.

## Feedback and community

- [Report a bug or request a feature](https://github.com/levinthal/levin-harrness/issues/new/choose). English and Chinese are both welcome.
- Join [Discord](https://discord.gg/yENT5KyBT) or the [Feishu community](https://applink.feishu.cn/client/chat/chatter/add_by_link?link_token=93blb389-88ea-4c04-a071-fbff366977ae&qr_code=true) for usage questions and research workflow discussions.
- Read [Support](SUPPORT.md) for what to include in a useful report.

[Website](https://levinthal.design/) · [Documentation](https://levinthal.design/docs.html) · [Terms of Service](https://levinthal.design/terms.html) · [Privacy Policy](https://levinthal.design/privacy.html)
