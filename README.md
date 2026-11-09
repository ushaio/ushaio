<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=58A6FF&center=true&vCenter=true&repeat=true&width=620&height=90&lines=Hi%2C%20%E6%88%91%E6%98%AF%20%E4%BA%91%E9%87%8C%E6%9C%89%E5%8F%AA%E7%8C%AB%20%F0%9F%90%B1;%E5%85%A8%E6%A0%88%E5%BC%80%E5%8F%91%E8%80%85%20%2F%20%E6%91%84%E5%BD%B1%E7%88%B1%E5%A5%BD%E8%80%85;Building%20Emulsion%20%26%20Open%20Source%20Tools" alt="云里有只猫 · 全栈开发与摄影 · Emulsion 和开源工具" />

**全栈开发者 | 摄影爱好者 | 开源工具作者**

用代码做顺手的工具，用照片和文字记录生活。

[![GitHub](https://img.shields.io/badge/GitHub-ushaio-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ushaio)
[![Blog](https://img.shields.io/badge/博客-shaio.top-E5591F?style=for-the-badge&logo=astro&logoColor=white)](https://shaio.top)
[![Emulsion](https://img.shields.io/badge/Emulsion-mo.shaio.top-2563EB?style=for-the-badge&logoColor=white)](https://mo.shaio.top)
[![Gallery](https://img.shields.io/badge/摄影画廊-mo--gallery.shaio.top-2EA043?style=for-the-badge&logo=googlephotos&logoColor=white)](https://mo-gallery.shaio.top)
[![Gmail](https://img.shields.io/badge/邮箱-shaiolww%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shaiolww@gmail.com)

</div>

---

## 🙋 关于我

我是 **云里有只猫 / Shai**，喜欢摄影，也喜欢把自己日常遇到的问题做成工具。

最近主要在做 **Emulsion / MO Gallery**：从个人摄影画廊出发，逐步把素材整理、图文写作、Zine 画册排版和独立站发布连在一起。希望拍下的照片、写下的故事，都有一个自己掌控的地方。

- 🖼️ **摄影与创作工具**：持续开发 MO Gallery Web、Emulsion 桌面工作台及配套插件。
- 🖥️ **桌面应用**：用 Go + Wails、Rust + Tauri、C# / WPF，做 Git 管理、照片调色和屏幕批注工具。
- 🌐 **全栈开发**：以 TypeScript、React / Next.js、Vue 为主，结合 Hono、Prisma、PostgreSQL 构建应用，也写 Java / Spring。
- 🤖 **AI 辅助开发与创作**：日常使用 Claude Code、Codex 等工具，也在项目中探索 AI 编辑器、MCP 与本地图像处理。
- ✍️ **记录与分享**：在 [博客](https://shaio.top) 写开发笔记，在 [个人画廊](https://mo-gallery.shaio.top) 分享摄影作品与故事。
- 📮 **联系我**：[shaiolww@gmail.com](mailto:shaiolww@gmail.com)

---

## 🖼️ 正在做：Emulsion / MO Gallery

**让素材留在自己手里，让照片与文字有自己的展示空间。**

[Emulsion](https://mo.shaio.top) 是正在持续开发的创作项目，官网目前处于内测阶段；**MO Gallery** 保留为 Web 端的技术标识。项目围绕以下几部分展开：

| 部分 | 正在做什么 | 入口 |
|---|---|---|
| **MO Gallery Web** | 自托管摄影站点与浏览器管理后台，管理照片、相册、胶卷、故事和博客；支持多种存储后端 | [开源仓库](https://github.com/ushaio/mo-gallery-web) · [我的摄影站](https://mo-gallery.shaio.top) |
| **Emulsion Desktop** | 基于 Go + Wails v3 + React 的桌面工作台，围绕素材管理、图文编辑、Zine 排版与 MCP 辅助创作持续迭代 | [客户端下载](https://mo.shaio.top/download) |
| **插件与扩展** | 官方插件市场索引与插件源码，扩展存储、图片预览和资源库能力 | [插件仓库](https://github.com/ushaio/mo-gallery-plugin) · [插件市场](https://mo.shaio.top/plugins) |

Web 端基于 **Next.js + React + Hono + Prisma + PostgreSQL**，支持本地文件系统、S3 兼容存储、Cloudflare R2 和 GitHub 存储，可通过 **Docker Compose、Vercel 或 Node.js** 部署。

[产品官网](https://mo.shaio.top) · [使用文档](https://mo.shaio.top/docs) · [创意广场](https://mo.shaio.top/plaza)

---

## 💡 开源项目

| 项目 | 介绍 | 技术 |
|---|---|---|
| 🖼️ **[MO Gallery Web](https://github.com/ushaio/mo-gallery-web)** ![Stars](https://img.shields.io/github/stars/ushaio/mo-gallery-web?style=flat&label=%E2%AD%90&color=2EA043) | 面向摄影展示与内容创作的自托管站点，包含公开前台、Web 后台、图文编辑与 AI 辅助 | TypeScript · Next.js · Hono · Prisma |
| 🌿 **[MyGit](https://github.com/ushaio/MyGit)** | 以 worktree 为中心的桌面 Git 客户端，统一管理多仓库与多个工作树，内置终端与 AI 提交信息生成 | Go · Wails v3 · React |
| 🎨 **[色迹 ChromaTrace](https://github.com/ushaio/ChromaTrace)** | 本地优先的 AI 追色与调色工作台，支持本地参数渲染、RAW 导入及 XMP / CUBE 预设 | Rust · Tauri 2 · React · WebGL2 |
| ✍️ **[ThinkCanvas](https://github.com/ushaio/ThinkCanvas)** ![Stars](https://img.shields.io/github/stars/ushaio/ThinkCanvas?style=flat&label=%E2%AD%90&color=2EA043) | Windows 输入路由验证与屏幕批注 Demo，支持数位板压感书写、整笔擦除和区域截图 | C# · WPF |
| 🧩 **[MO Gallery Plugin](https://github.com/ushaio/mo-gallery-plugin)** | 桌面端插件市场索引与官方插件源码，包含图片预览、人脸等扩展及签名安装包校验 | TypeScript · Node.js |

---

## 🛠️ 技术栈

<div align="center">

**Web 与服务端**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java%20%2F%20Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)

**桌面与图像处理**

![Go](https://img.shields.io/badge/Go%20%2F%20Wails-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust%20%2F%20Tauri-000000?style=flat-square&logo=rust&logoColor=white)

**AI 与工程工具**

![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-412991?style=flat-square&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-181717?style=flat-square)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

</div>

---

## 🌐 找到我和我的作品

| 入口 | 内容 |
|---|---|
| [Emulsion 官网](https://mo.shaio.top) | 项目介绍、客户端下载、使用文档与创意广场（内测中） |
| [个人摄影画廊](https://mo-gallery.shaio.top) | 用 MO Gallery 搭建的个人摄影站，收藏照片与影像故事 |
| [个人博客](https://shaio.top) | 开源项目进展、开发笔记、摄影与生活记录 |

---

## 📊 GitHub 统计

<div align="center">

<img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ushaio&theme=github" alt="GitHub 贡献概览" />
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ushaio&theme=github" alt="仓库语言分布" />
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ushaio&theme=github" alt="提交语言分布" />

<img height="150" src="https://streak-stats.demolab.com?user=ushaio&hide_border=true&locale=zh_Hans" alt="GitHub 连续贡献统计" />

</div>

---

<div align="center">

**Ad Astra Per Aspera** ✨

欢迎试用、提 Issue，或分享你的摄影与创作方式。

</div>
