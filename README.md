<a name="levin-harness"></a>
<h1 align="center">
  <img src="assets/wordmark-on-light.png?v=3#gh-light-mode-only" width="320" alt="Lévin™ Harness" />
  <img src="assets/wordmark-on-dark.png?v=3#gh-dark-mode-only" width="320" alt="Lévin™ Harness" />
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

Before installing or using the app, read the [Terms of Service](TERMS.md), [Privacy Policy](PRIVACY.md), and [License Notice](LICENSE.md).

GitHub's **Code > Download ZIP** and automatically generated **Source code** archives contain this repository's documentation and images, not the application.

## One workspace for scientific work

### Molecular workspace

Inspect a structure in Mol*, select a chain or residue range, and bring it into the conversation. Structures, selections, and measurements become structured context for the agent, so you can discuss exact molecular details while it helps inspect, measure, and adjust the view.

![Top7 structure in Mol* with molecular representations open beside the agent conversation](assets/molecular-context.webp)

[Explore the molecular workspace](https://levinthal.design/molecular-workspace.html)

### Scientific plugins

Use tools such as ProteinMPNN, FAMPNN, ThermoMPNN, and RFantibody from a conversation or workflow. Plugins bring together skills, MCP tools, and managed runtimes, with supported deployments on your Mac or an SSH GPU host. To add another scientific tool, the built-in plugin creator can help inspect its GitHub repository, package it, and verify a real run.

![Scientific plugin catalog with capability categories, plugin cards, MCP status, and deployment counts](assets/scientific-plugins.webp)

[Browse plugins and create your own](https://levinthal.design/plugins.html)

### Research workflows

Describe your method in natural language, then refine the steps and branches with the agent on the same live canvas. Build turns the graph into a callable Skill; test it with sample inputs and review the agent's report for each step. The antibody-design canvas below connects sequence design, scoring, relaxation, and stability analysis.

![Lévin™ Harness showing an antibody design workflow on a visual canvas alongside an agent conversation](assets/workflows.webp)

[Explore research workflows](https://levinthal.design/workflows.html)

### Remote GPU and background jobs

Connect your own Linux GPU host over SSH to deploy supported plugins and run compute tasks. Jobs track status, execution details, and returned files beyond a single chat turn, and monitoring recovers after reconnecting or restarting the app. Bring the output back into your local project to review sequences, compare scores, and decide what to run next.

![Completed ProteinMPNN jobs with returned FASTA sequences and JSON, Markdown, and CSV reports alongside the agent's result review](assets/compute-jobs.webp)

[Connect a remote GPU](https://levinthal.design/remote-gpu.html) · [See how Jobs work](https://levinthal.design/jobs.html)

### Persistent research goals

Define the result you want, the constraints, and the evidence that will count as completion. Goal mode carries the work across turns, checks progress against files and execution results, and can wait for background jobs before continuing. Review phase updates, adjust the objective, or pause the work as the research develops.

![An active ProteinMPNN research goal moving from positional-preference verification to final delivery, with phase updates and pause controls](assets/research-goals.webp)

[Explore persistent goals](https://levinthal.design/goals.html)

### Your choice of model

Configure your preferred supported provider or a compatible endpoint, including private and self-hosted services. Keep multiple configurations, test the connection, and choose the default model for your work.

![Model settings with saved provider configurations and a New Provider form for the endpoint, API key, and model](assets/model-providers.webp)

[Set up your model provider](https://levinthal.design/install.html)

## Get started

1. **Install the app.** Download the `.dmg`, open it, and drag Lévin™ Harness into **Applications**.
2. **Connect a model.** Open **Settings > Model > New provider**, enter your provider configuration, run **Test Connection**, and save it as the default model.
3. **Open a project.** Choose a local folder, review the task permissions, and start a conversation. Try asking the agent to list the project files or summarize a document.

See the [installation guide](https://levinthal.design/install.html) for the complete setup. A remote GPU is optional.

## FAQ

### Which platforms are supported?

The current preview supports macOS on Apple silicon. Builds for Intel Macs, Windows, and Linux are not currently available. A Linux GPU machine can be connected as a remote compute host.

### Is Lévin™ Harness free?

The preview is currently free for non-commercial use, subject to the [Terms of Service](TERMS.md). Model providers may charge separately for usage; those fees are not included with Lévin™ Harness.

### Where does my data go?

Projects, conversations, settings, and API keys are stored locally by default. Task content is sent to the model provider you configure, and remote tasks may transfer the inputs needed by your chosen compute host. Review the [Privacy Policy](PRIVACY.md) and your provider's settings for details.

### Is this an open-source project?

The Lévin™ Harness application source code is not public. This repository provides product information, release downloads, and a place to report problems or request features. Using an integrated open-source tool does not make the application itself open source; individual tools have their own terms.

## License and legal documents

The application is proprietary software. Non-commercial use is permitted under the Terms; modification, redistribution, and commercial use require separate written permission.

| Document | English | 简体中文 |
| --- | --- | --- |
| License notice | [License](LICENSE.md#english) | [许可说明](LICENSE.md#中文) |
| Terms of Service | [Full text](TERMS.md) | [用户服务协议全文](TERMS.zh-CN.md) |
| Privacy Policy | [Full text](PRIVACY.md) | [隐私政策全文](PRIVACY.zh-CN.md) |

The Terms and Privacy Policy are reproduced from the website, version **V1.0**, with an effective date of **September 10, 2026**. The Chinese text prevails where the language versions differ, as specified in each document.

## Feedback and community

- [Report a bug or request a feature](https://github.com/levinthal/levin-harrness/issues/new/choose). English and Chinese are both welcome.
- Join [Discord](https://discord.gg/yENT5KyBT) or the [Feishu community](https://applink.feishu.cn/client/chat/chatter/add_by_link?link_token=93blb389-88ea-4c04-a071-fbff366977ae&qr_code=true) for usage questions and research workflow discussions.
- Read [Support](SUPPORT.md) for what to include in a useful report.

[Website](https://levinthal.design/) · [Documentation](https://levinthal.design/docs.html) · [License](LICENSE.md) · [Terms of Service](TERMS.md) · [Privacy Policy](PRIVACY.md)
