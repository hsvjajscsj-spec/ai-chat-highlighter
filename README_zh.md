<p align="center">
  <a href="./README.md">English</a> | 简体中文
</p>

<h1 align="center">Chat Highlight</h1>

<p align="center">
  <strong>面向 ChatGPT、Claude、Gemini 的 AI 对话高亮工具</strong>
</p>

<p align="center">
  把有用的 AI 回答保存为结构化笔记，并导出到 Markdown、HTML、TXT 或 Notion。
</p>

<p align="center">
  <a href="https://chromewebstore.google.com/detail/chat-highlight-auto-chatg/ffnhgclfemimnnbkbhebjbobiipgkgbk?utm_source=github&utm_medium=readme&utm_campaign=repo_launch"><img alt="Chrome Web Store" src="https://img.shields.io/badge/Chrome%20Web%20Store-Install-4285F4?logo=googlechrome&logoColor=white"></a>
  <a href="https://chromewebstore.google.com/detail/chat-highlight-auto-chatg/ffnhgclfemimnnbkbhebjbobiipgkgbk?utm_source=github&utm_medium=readme&utm_campaign=repo_launch"><img alt="Chrome Web Store rating" src="https://img.shields.io/chrome-web-store/rating/ffnhgclfemimnnbkbhebjbobiipgkgbk?label=rating&color=ffd000"></a>
  <a href="https://chat-highlight.com/docs.html"><img alt="Documentation" src="https://img.shields.io/badge/Docs-User%20Guide-blue"></a>
  <a href="https://chat-highlight.com/"><img alt="Homepage" src="https://img.shields.io/badge/Website-chat--highlight.com-success"></a>
</p>

Chat Highlight 是一款本地优先的 Chrome 扩展，用于高亮、结构化和导出 **ChatGPT**、**Claude**、**Gemini** 对话。你可以保存 prompts、answers、代码块、笔记、图片和标签，并导出为 **Markdown**、**HTML**、**TXT**，或直接发送到 **Notion**。

<div align="center">
  <img src="https://chat-highlight.com/images/og-share.png" alt="Chat Highlight AI 对话高亮工具宣传图" width="100%" style="border-radius: 8px;">
</div>

<br>

## 🎥 演示视频

<div align="center">

[![Chat Highlight 功能演示](https://img.youtube.com/vi/ehp6oAzvA00/hqdefault.jpg)](https://www.youtube.com/watch?v=ehp6oAzvA00)

</div>

> [!NOTE]
> **仓库说明：** 这个仓库是 Chat Highlight 的官方社区入口，用于收集 Issue、功能建议、文档链接和公开路线说明。
> 为保护核心 DOM 解析与云同步基础设施，扩展源码目前暂不开源。产品本身坚持 **Local-First（本地优先）**：除非你主动开启云同步，否则高亮、笔记和标签默认保存在浏览器本地。

---

## 🔥 为什么需要 Chat Highlight？

AI 对话已经变成研究笔记、编程助手和头脑风暴空间。但问题是，真正有价值的回答很容易被聊天历史淹没。

| 问题 | 没有专门 AI 对话高亮工具时会发生什么 |
| :--- | :--- |
| ❌ 上下文丢失 | 几周前 ChatGPT、Claude 或 Gemini 给出的关键答案很难再找回。 |
| ❌ 代码格式崩坏 | 复制代码块后缩进、语言上下文或可读结构丢失。 |
| ❌ 长对话难导航 | 想在 50 轮研究对话里找到某个 prompt，只能反复滚动。 |
| ❌ 笔记散落 | 高亮、标签、图片和后续想法散在多个工具里。 |

**Chat Highlight 会把长 AI 对话整理成结构化、可搜索、可导出的知识卡片；你可以本地保存、跨设备同步，或导出到 Notion。**

---

## 🎯 工作流

| 🌐 阅读 | 🎨 高亮 | 🌲 结构化 | 🔎 搜索 | 📤 导出 |
| :---: | :---: | :---: | :---: | :---: |
| 打开 ChatGPT、Claude、Gemini 或任意网页 | 选择文本、代码或图片 | 区分 prompt、answer、笔记和标签 | 使用侧边栏或 Cloud Dashboard | Markdown、HTML、TXT 或 Notion |

---

## ✨ 核心功能

### 🤖 AI 原生对话高亮

Chat Highlight 可以识别受支持 AI 聊天页面的结构，覆盖 **ChatGPT**、**Claude** 和 **Gemini**。它会帮助你区分提问与回答，把混乱的对话整理成清晰大纲。

<div align="center">
  <img src="https://chat-highlight.com/images/1.png" alt="ChatGPT Claude Gemini AI 对话高亮" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 🌲 树状侧边栏与实时目录

用层级化 Tree View 管理长对话，按标签过滤，跳转到指定 prompt，并在不丢失上下文的情况下直接编辑笔记。

<div align="center">
  <img src="https://chat-highlight.com/images/2.png" alt="结构化侧边栏和实时目录" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 📊 Cloud Dashboard

在一个可视化看板里搜索高亮、标签、图片和已保存页面。免费用户可以使用本地高亮与有限云备份；付费计划提供更多云同步容量和历史记录能力。

<div align="center">
  <img src="https://chat-highlight.com/images/3.png" alt="AI 对话高亮云端看板" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 📤 导出 Markdown、HTML、TXT 和 Notion

你可以把结构化笔记本地导出为 **Markdown**、**HTML** 或 **TXT**，也可以直接发送到 **Notion**。HTML 导出会尽量保留 AI 对话的视觉结构，包括更易阅读的代码块。

<div align="center">
  <img src="https://chat-highlight.com/images/4.png" alt="导出 AI 对话到 Markdown HTML TXT 和 Notion" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 🔒 本地优先隐私

默认情况下，高亮、笔记、标签和页面数据会通过 `chrome.storage.local` 保存在你的浏览器本地。云同步是可选的。我们不会使用你的私人笔记训练 AI 模型。

---

## 🎨 高亮分类

| 颜色 | 类别 | 适合保存的内容 |
| :--- | :--- | :--- |
| 🟡 黄色 | **重点** | 关键结论、重要决策、最终答案 |
| 🟢 绿色 | **摘录** | 代码片段、API 参考、可复用文本 |
| 🔵 蓝色 | **事实** | 证据、数据点、引用来源 |
| 🔴 粉色 | **问题** | 追问、bug、待验证事项 |
| 🟣 紫色 | **灵感** | 想法、头脑风暴、创意火花 |

---

## ⚔️ Chat Highlight 与普通高亮工具的区别

| 功能 | Chat Highlight | 普通网页高亮工具 |
| :--- | :---: | :---: |
| AI 对话结构识别 | ✅ 支持 | ❌ 通常不支持 |
| Prompt / Answer 整理 | ✅ 支持 | ❌ 不支持 |
| Tree View 与实时目录 | ✅ 支持 | ⚠️ 很少支持 |
| 代码友好导出 | ✅ 支持 | ⚠️ 常降级为纯文本 |
| 本地优先存储 | ✅ 支持 | ⚠️ 视工具而定 |
| 直接导出 Notion | ✅ 支持 | ⚠️ 视工具而定 |

---

## 🚀 安装使用

1. 从 [Chrome Web Store](https://chromewebstore.google.com/detail/chat-highlight-auto-chatg/ffnhgclfemimnnbkbhebjbobiipgkgbk?utm_source=github&utm_medium=readme&utm_campaign=repo_launch) 安装 Chat Highlight。
2. 打开 ChatGPT、Claude、Gemini 或任意网页。
3. 选择文本、代码或图片。
4. 高亮、加标签、写笔记，并在需要时导出。

---

## 🤝 社区与支持

- 遇到 bug？欢迎提交 [Issue](../../issues)。
- 有功能建议？欢迎提交 [feature request](../../issues/new)。
- 需要帮助？查看 [官方文档](https://chat-highlight.com/docs.html)。
