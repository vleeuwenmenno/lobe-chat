<a name="readme-top"></a>

<div align="center">

<img height="120" src="https://registry.npmmirror.com/@lobehub/assets-logo/1.0.0/files/assets/logo-3d.webp">
<img height="120" src="https://gw.alipayobjects.com/zos/kitchen/qJ3l3EPsdW/split.svg">
<img height="120" src="https://registry.npmmirror.com/@lobehub/assets-emoji/1.3.0/files/assets/robot.webp">

<h1>Lobe Chat</h1>

LobeChat 是一个开源的、可扩展的（[Function Calling][fc-url]）高性能聊天机器人框架。<br/> 它支持一键免费部署私人 ChatGPT/LLM 网页应用程序。

[English](./README.md) · **简体中文** · [更新日志](./CHANGELOG.md) · [文档][wiki-url] · [报告问题][issues-url] · [请求功能][issues-url]

<!-- SHIELD GROUP -->

[![release][release-shield]][release-url]
[![releaseDate][release-date-shield]][release-date-url]
[![][license-shield]][fossa-license-url]
[![ciTest][ci-test-shield]][ci-test-url]
[![ciRelease][ci-release-shield]][ci-release-url] <br/>
[![contributors][contributors-shield]][contributors-url]
[![forks][forks-shield]][forks-url]
[![stargazers][stargazers-shield]][stargazers-url]
[![issues][issues-shield]][issues-url]

[![Deploy with Vercel][deploy-button-image]][deploy-url]

![](https://gw.alipayobjects.com/zos/kitchen/RKnWrrfuMl/welcome.webp)

</div>

<details>
<summary><kbd>目录树</kbd></summary>

#### TOC

- [👋🏻 开始使用 & 交流](#-开始使用--交流)

- [✨ 功能特性](#-功能特性)

- [📸 快照预览](#-快照预览)

- [🛳 开箱即用](#-开箱即用)

  - [保持更新](#保持更新)

- [📦 生态系统](#-生态系统)

- [🧩 插件体系](#-插件体系)

- [⌨️ 本地开发](#️-本地开发)

- [🤝 参与贡献](#-参与贡献)

- [🔗 更多工具](#-更多工具)

####

<br/>

</details>

## 👋🏻 开始使用 & 交流

我们是一群充满热情的设计工程师，希望为 AIGC 提供现代化的设计组件和工具，并以开源的方式分享，以促进它们在更广泛的社区中的发展和采用，LobeChat 目前正在积极开发中，有需求或者问题，欢迎提交 [issues][issues-url]

| [![][official-shield]][official-url] | 无需安装或注册！访问我们的网站，快速体验                                     |
| :----------------------------------- | :--------------------------------------------------------------------------- |
| [![][discord-shield]][discord-url]   | 加入我们的 Discord 社区！这是你可以与开发者和其他 LobeHub 热衷用户交流的地方 |

![](https://gw.alipayobjects.com/zos/kitchen/0hcO8QiU9c/star.webp)

> **⭐️ 给我们点赞：** 你将从 GitHub 上无延迟地接收所有发布通知！

## ✨ 功能特性

- [x] 💨 **快速部署**：使用 Vercel 平台，只需点击一键部署按钮，即可在 1 分钟内完成部署，无需复杂的配置过程；
- [x] 💎 **精致 UI 设计**：经过精心设计的界面，具有优雅的外观和流畅的交互效果，支持亮暗色主题，适配移动端。支持 PWA，提供更加接近原生应用的体验；
- [x] 🗣️ **流畅的对话体验**：流式响应带来流畅的对话体验，并且支持完整的 Markdown 渲染，包括代码高亮、LaTex 公式、Mermaid 流程图等；
- [x] 🧩 **支持插件与自定义插件开发**：会话支持插件扩展，用户可以安装和使用各种插件，例如搜索引擎、网页提取等，同时也支持自定义插件的开发，满足自定义需求；
- [x] 🔒 **隐私安全**：所有数据保存在用户浏览器本地，保证用户的隐私安全；
- [x] 🤖 **自定义助手角色**：用户可以根据自己的需求创建、分享和调试个性化的对话助手角色，提供更加灵活和个性化的对话功能；
- [x] 🌐 **自定义域名**：如果用户拥有自己的域名，可以将其绑定到平台上，方便在任何地方快速访问对话助手。
- [x] 🏬 **角色市场**：提供角色市场，用户可以在市场上选择自己喜欢的对话助手角色，丰富对话的内容和风格；

> **👉 Roadmap：** 你可以在 Projects 中找到我们后续的 [Roadmap][project-url] 计划

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## 📸 快照预览

![](https://gw.alipayobjects.com/zos/kitchen/69x6bllkX3/pwa.webp)

**PWA 渐进式 Web 应用**

利用渐进式 Web 应用 [PWA](https://support.google.com/chrome/answer/9658361) 技术，您可在电脑或移动设备上实现流畅的 LobeChat 体验。

> **Note**\
> 若您未熟悉 PWA 的安装过程，您可以按照以下步骤将 LobeChat 添加为您的桌面应用（也适用于移动设备）：
>
> - 在电脑上运行 Chrome 或 Edge 浏览器
> - 访问 LobeChat 网页
> - 在地址栏的右上角，单击 <kbd>安装</kbd> 图标
> - 根据屏幕上的指示完成 PWA 的安装

<br/>

![](https://gw.alipayobjects.com/zos/kitchen/pvus1lo%26Z7/darkmode.webp)

**主题模式选择**

LobeChat 提供了亮色和暗色两种主题模式以及颜色定制选项，默认情况下，主题会跟随系统设置，您也可以在设置中手动切换。

<br/>

![](https://gw.alipayobjects.com/zos/kitchen/R441AuFS4W/mobile.webp)

**移动设备适配**

我们针对移动设备进行了一系列适配设计以提升用户体验。目前我们正在对移动端的体验进行版本迭代，如果您有任何建议或想法，我们非常欢迎您提供反馈。

> 🚧 更多快照和演示正在陆续添加中...

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## 🛳 开箱即用

LobeChat 提供了 Vercel 的 [自托管版本][deploy-url]。这使你可以在几分钟内构建自己的聊天机器人，无需任何基础知识。如果想自己部署该服务，可以按照以下步骤进行操作：

- 准备好你的 [OpenAI API Key](https://platform.openai.com/account/api-keys) 。
- 点击下方按钮开始部署： Deploy with Vercel，直接使用 Github 账号登录即可，记得在环境变量页填入 API Key 和页面访问密码 CODE；
- 部署完毕后，即可开始使用；
- 绑定自定义域名（可选）：Vercel 分配的域名 DNS 在某些区域被污染了，绑定自定义域名即可直连。

[![使用 Vercel 部署][deploy-button-image]][deploy-url]

> **Note**\
> 本项目提供了一些额外的配置项，使用环境变量进行设置：

| 环境变量           | 类型 | 描述                                                                                   | 示例                                                                   |
| ------------------ | ---- | -------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| `OPENAI_API_KEY`   | 必选 | 这是你在 OpenAI 账户页面申请的 API 密钥                                                | `sk-xxxxxx...xxxxxx`                                                   |
| `OPENAI_PROXY_URL` | 可选 | 如果你手动配置了 OpenAI 接口代理，可以使用此配置项来覆盖默认的 OpenAI API 请求基础 URL | `https://api.chatanywhere.cn`<br/>默认值:<br/>`https://api.openai.com` |
| `ACCESS_CODE`      | 可选 | 添加访问此服务的密码，密码应为 6 位数字或字母                                          | `awCT74` 或 `e3@09!`                                                   |

### 保持更新

如果你根据 README 中的一键部署步骤部署了自己的项目，你可能会发现总是被提示“有可用更新”。这是因为 Vercel 默认为你创建新项目而非 fork 本项目，这将导致无法准确检测更新。我们建议按照 [📘 LobeChat 自部署保持更新](https://github.com/lobehub/lobe-chat/wiki/Upstream-Sync.zh-CN) 步骤重新部署。

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## 📦 生态系统

| NPM                            | 代码库                                | 描述                                                                                                  | 版本                                   |
| ------------------------------ | ------------------------------------- | ----------------------------------------------------------------------------------------------------- | -------------------------------------- |
| [@lobehub/ui][lobe-ui-url]     | [lobehub/lobe-ui][lobe-ui-github]     | Lobe UI 是一个专为构建 AIGC 网页应用程序而设计的开源 UI 组件库。                                      | [![][lobe-ui-shield]][lobe-ui-url]     |
| [@lobehub/lint][lobe-lint-url] | [lobehub/lobe-lint][lobe-lint-github] | LobeLint 为 LobeHub 提供 ESlint，Stylelint，Commitlint，Prettier，Remark 和 Semantic Release 的配置。 | [![][lobe-lint-shield]][lobe-lint-url] |
| @lobehub/assets                | [lobehub/assets][lobe-assets-github]  | LobeHub 的 Logo 资源、favicon、网页字体。                                                             |                                        |

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## 🧩 插件体系

插件提供了扩展 LobeChat [Function Calling][fc-url] 能力的方法。可以用于引入新的 Function Calling，甚至是新的消息结果渲染方式。如果你对插件开发感兴趣，请在 Wiki 中查阅我们的 [📘 插件开发指引](https://github.com/lobehub/lobe-chat/wiki/Plugin-Development.zh-CN) 。

> **Note**\
> 插件系统目前正在进行重大开发。您可以在以下 Issues 中了解更多信息:
>
> - [x] [**插件一期**](https://github.com/lobehub/lobe-chat/issues/73): 实现插件与主体分离，将插件拆分为独立仓库维护，并实现插件的动态加载
> - [x] [**插件二期**](https://github.com/lobehub/lobe-chat/issues/97): 插件的安全性与使用的稳定性，更加精准地呈现异常状态，插件架构的可维护性与开发者友好
> - [ ] [**插件三期**](https://github.com/lobehub/lobe-chat/issues/149)：更高阶与完善的自定义能力，支持插件鉴权与示例

- [@lobehub/lobe-chat-plugins][lobe-chat-plugins]：这是 LobeChat 的插件索引。它从该仓库的 index.json 中获取插件列表并显示给用户。
- [@lobehub/chat-plugin-sdk][chat-plugin-sdk]：LobeChat 插件 SDK 可帮助您创建出色的 Lobe Chat 插件。
- [@lobehub/chat-plugins-gateway][chat-plugins-gateway]：LobeChat 插件网关是一个后端服务，作为 LobeChat 插件的网关。我们使用 Vercel 部署此服务。主要的 API POST /api/v1/runner 被部署为 Edge Function。

| 官方插件                                 | 描述                                                                         |
| ---------------------------------------- | ---------------------------------------------------------------------------- |
| [搜索引擎][chat-plugin-search-engine]    | 此插件允许使用 SerpApi 搜索引擎。                                            |
| [实时天气][chat-plugin-realtime-weather] | 此插件通过获取实时天气数据提供实用的天气信息，并可以根据用户的位置自动更新。 |
| [网站爬虫][chat-plugin-web-crawler]      | 此插件自动爬取指定 URL 网页的主要内容，并将其用作上下文输入。                |

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## ⌨️ 本地开发

可以使用 Gitpod 进行在线开发：

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)][gitpod-url]

或者使用以下命令进行本地开发：

```bash
$ git clone https://github.com/lobehub/lobe-chat.git
$ cd lobe-chat
$ pnpm install
$ pnpm dev
```

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## 🤝 参与贡献

我们非常欢迎各种形式的贡献。如果你对贡献代码感兴趣，可以查看我们的 GitHub [Issues][issues-url] 和 [Projects][project-url]，大展身手，向我们展示你的奇思妙想。

[![][pr-welcome-shield]][pr-welcome-url]
[![][submit-agents-shield]][submit-agents-url]
[![][submit-plugin-shield]][submit-plugin-url]

[![][contributors-contrib]][contributors-url]

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## 🔗 更多工具

- [🤯 Lobe Theme][lobe-theme] : Stable Diffusion WebUI 的现代主题，精致的界面设计，高度可定制的 UI，以及提高效率的功能。
- [🌏 Lobe i18n][lobe-i18n] : Lobe i18n 是一个由 ChatGPT 驱动的 i18n（国际化）翻译过程的自动化工具。它支持自动分割大文件、增量更新，以及为 OpenAI 模型、API 代理和温度提供定制选项的功能。
- [💌 Lobe Commit][lobe-commit] : Lobe Commit 是一个 CLI 工具，它利用 Langchain/ChatGPT 生成基于 Gitmoji 的提交消息。

<div align="right">

[![][back-to-top]](#readme-top)

</div>

---

<details><summary><h4>📝 License</h4></summary>

[![][fossa-license-shield]][fossa-license-url]

</details>

Copyright © 2023 [LobeHub][profile-url]. <br />
This project is [MIT](./LICENSE) licensed.

<!-- LINK GROUP -->

[back-to-top]: https://img.shields.io/badge/-BACK_TO_TOP-151515?style=flat-square
[chat-plugin-realtime-weather]: https://github.com/lobehub/chat-plugin-realtime-weather
[chat-plugin-sdk]: https://github.com/lobehub/chat-plugin-sdk
[chat-plugin-search-engine]: https://github.com/lobehub/chat-plugin-search-engine
[chat-plugin-web-crawler]: https://github.com/lobehub/chat-plugin-web-crawler
[chat-plugins-gateway]: https://github.com/lobehub/chat-plugins-gateway
[ci-release-shield]: https://github.com/lobehub/lobe-chat/workflows/Release%20CI/badge.svg
[ci-release-url]: https://github.com/lobehub/lobe-chat/actions?query=workflow%3ARelease%20CI
[ci-test-shield]: https://github.com/lobehub/lobe-chat/workflows/Test%20CI/badge.svg
[ci-test-url]: https://github.com/lobehub/lobe-chat/actions/workflows/test.yml
[contributors-contrib]: https://contrib.rocks/image?repo=lobehub/lobe-chat
[contributors-shield]: https://img.shields.io/github/contributors/lobehub/lobe-chat.svg?style=flat
[contributors-url]: https://github.com/lobehub/lobe-chat/graphs/contributors
[deploy-button-image]: https://vercel.com/button
[deploy-url]: https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Flobehub%2Flobe-chat&env=OPENAI_API_KEY&envDescription=Find%20your%20OpenAI%20API%20Key%20by%20click%20the%20right%20Learn%20More%20button.%20%20&envLink=https%3A%2F%2Fplatform.openai.com%2Faccount%2Fapi-keys&project-name=lobe-chat&repository-name=lobe-chat
[discord-shield]: https://dcbadge.vercel.app/api/server/AYFPHvv2jT?style=for-the-badge
[discord-url]: https://discord.gg/AYFPHvv2jT
[fc-url]: https://sspai.com/post/81986
[forks-shield]: https://img.shields.io/github/forks/lobehub/lobe-chat.svg?style=flat
[forks-url]: https://github.com/lobehub/lobe-chat/network/members
[fossa-license-shield]: https://app.fossa.com/api/projects/git%2Bgithub.com%2Flobehub%2Flobe-chat.svg?type=large
[fossa-license-url]: https://app.fossa.com/projects/git%2Bgithub.com%2Flobehub%2Flobe-chat
[gitpod-url]: https://gitpod.io/#https://github.com/lobehub/lobe-chat
[issues-shield]: https://img.shields.io/github/issues/lobehub/lobe-chat.svg?style=flat
[issues-url]: https://img.shields.io/github/issues/lobehub/lobe-chat.svg?style=flat
[license-shield]: https://app.fossa.com/api/projects/git%2Bgithub.com%2Flobehub%2Flobe-chat.svg?type=shield&issueType=license
[lobe-assets-github]: https://github.com/lobehub/lobe-assets
[lobe-chat-plugins]: https://github.com/lobehub/lobe-chat-plugins
[lobe-commit]: https://github.com/lobehub/lobe-commit/tree/master/packages/lobe-commit
[lobe-i18n]: https://github.com/lobehub/lobe-commit/tree/master/packages/lobe-i18n
[lobe-lint-github]: https://github.com/lobehub/lobe-lint
[lobe-lint-shield]: https://img.shields.io/npm/v/@lobehub/lint?label=%F0%9F%A4%AF%20NPM
[lobe-lint-url]: https://www.npmjs.com/package/@lobehub/lint
[lobe-theme]: https://github.com/lobehub/sd-webui-lobe-theme
[lobe-ui-github]: https://github.com/lobehub/lobe-ui
[lobe-ui-shield]: https://img.shields.io/npm/v/@lobehub/ui?label=%F0%9F%A4%AF%20NPM
[lobe-ui-url]: https://www.npmjs.com/package/@lobehub/ui
[official-shield]: https://img.shields.io/website?down_message=offline&label=🤯%20Try%20LobeChat&up_message=online&url=https%3A%2F%2Flobe-chat.vercel.app&style=for-the-badge
[official-url]: https://lobe-chat.vercel.app
[pr-welcome-shield]: https://img.shields.io/badge/🤯_pr_welcome-%E2%86%92-FEE064?style=for-the-badge
[pr-welcome-url]: https://github.com/lobehub/lobe-chat/pulls
[profile-url]: https://github.com/lobehub
[project-url]: https://github.com/lobehub/lobe-chat/projects
[release-date-shield]: https://img.shields.io/github/release-date/lobehub/lobe-chat?style=flat
[release-date-url]: https://github.com/lobehub/lobe-chat/releases
[release-shield]: https://img.shields.io/npm/v/@lobehub/chat?label=%F0%9F%A4%AF%20Chat
[release-url]: https://www.npmjs.com/package/@lobehub/chat
[stargazers-shield]: https://img.shields.io/github/stars/lobehub/lobe-chat.svg?style=flat
[stargazers-url]: https://github.com/lobehub/lobe-chat/stargazers
[submit-agents-shield]: https://img.shields.io/badge/🤖/🏪_submit_agent-%E2%86%92-9DFF92?style=for-the-badge
[submit-agents-url]: https://github.com/lobehub/lobe-chat-agents
[submit-plugin-shield]: https://img.shields.io/badge/🧩/🏪_submit_plugin-%E2%86%92-50E3C2?style=for-the-badge
[submit-plugin-url]: https://github.com/lobehub/lobe-chat-plugins
[wiki-url]: https://github.com/lobehub/lobe-chat/wiki
