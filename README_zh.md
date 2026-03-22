<div align="center">

[English](./README.md) | 简体中文

</div>

# 🧠 Chat Highlight: 专为 AI 对话打造的终极高亮与导出工具

<div align="center">

[![Chrome 应用商店](https://img.shields.io/badge/获取插件-Chrome商店-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/chat-highlight-auto-chatg/ffnhgclfemimnnbkbhebjbobiipgkgbk?utm_source=github&utm_medium=readme&utm_campaign=repo_launch) [![Chrome Web Store Rating](https://img.shields.io/chrome-web-store/rating/ffnhgclfemimnnbkbhebjbobiipgkgbk?label=rating&style=for-the-badge&color=ffd000)](https://chromewebstore.google.com/detail/chat-highlight-auto-chatg/ffnhgclfemimnnbkbhebjbobiipgkgbk?utm_source=github&utm_medium=readme&utm_campaign=repo_launch) [![官方文档](https://img.shields.io/badge/阅读-官方帮助文档-blue?style=for-the-badge)](https://chat-highlight.com/docs.html) [![官网](https://img.shields.io/badge/访问官网-chat--highlight.com-success?style=for-the-badge)](https://chat-highlight.com/)

</div>

**别再手动复制粘贴你的 AI 聊天记录了。**

Chat Highlight 是一款“AI 原生”的浏览器扩展程序。它能自动格式化、高亮并一键导出你的 **ChatGPT** 和 **Gemini** 深度对话，生成完美的 Markdown 笔记。

<div align="center">
  <img src="https://chat-highlight.com/images/og-share.png" alt="Chat Highlight 宣传海报" width="100%" style="border-radius: 8px;">
</div>

<br>

## 🎥 1 分钟演示与使用教程

<div align="center">

[![Chat Highlight 功能演示](https://img.youtube.com/vi/ehp6oAzvA00/hqdefault.jpg)](https://www.youtube.com/watch?v=ehp6oAzvA00)

</div>

> [!NOTE]
> 💡 **关于闭源的特别说明：** 本代码仓库是我们的官方**社区反馈中心（Community Hub）**，用于汇集 Bug 反馈 (Issue)、功能许愿池以及产品路线图。
> 为了维护核心 DOM 解析引擎与云端基建的长期健康发展，插件源码目前**暂不开源**。但请放心，我们坚决信奉 **Local-First（本地优先）** 哲学：除非你主动开启云同步，否则你所有的知识抓取轨迹都仅保存在浏览器本地，拥有彻底的隐私！

---

## 🔥 为什么选择 Chat Highlight？(直击痛点)

如果你是程序员、研究员或重度 AI 依赖者，以下灾难场景你一定很熟悉：

| ❌ 典型痛点 | 灾难级的低效工作流 |
| :--- | :--- |
| **灵感遗失** | 几周前在 ChatGPT 里调试出的一套绝妙架构方案，关掉网页后死活找不到了。 |
| **代码崩坏** | 辛苦圈选 AI 给的代码块复制到 IDE 或 Notion，结果缩进全无、语法高亮尽毁。 |
| **大海捞针** | 在一个长达 50 多个回合的漫长 Debug 对话中，想跳回最初的报错日志简直痛不欲生。 |

✅ **Chat Highlight 的使命，就是在你的 AI 对话页面与你的“第二大脑”（Notion/Obsidian）之间，修筑一条无损的数据传输高铁。**

---

## 🎯 高效工作流：从网页到个人知识库

搭配 Chat Highlight，收集知识只需极简五步：

| 🌐 浏览 | 🖱️ 选取 | 🎨 高亮 | 📝 整理 | ☁️ 导出与同步 |
| :---: | :---: | :---: | :---: | :---: |
| 研读 AI 长文 | 选中文本/代码 | 选择颜色分类 | 加个标签 (Tag) | 发送至云端/Notion |

---

## ✨ 核心功能亮点

### 🤖 AI 原生提取 (Auto-highlight AI Chats)

别再手动复制粘贴了！Chat Highlight 能够自动识别 **ChatGPT 和 Gemini** 中的对话结构，瞬间分离你的“提问 (Prompts)”与 AI 的“回答 (Answers)”，将碎片化的对话变成永久的、结构化的知识切片。

<div align="center">
  <img src="https://chat-highlight.com/images/1.png" alt="Auto-highlight AI Chats" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 🌲 树状大纲侧边栏 (Structured Sidebar)

无需再漫无目的地反复滚动历史记录。通过清晰的**树状视图 (Tree View)** 分层管理你的高亮笔记。支持按标签过滤、一键跳转到对应问题，甚至能在不丢失上下文的情况下直接在侧边栏编辑笔记。

<div align="center">
  <img src="https://chat-highlight.com/images/2.png" alt="Structured Sidebar" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 📊 可视化云端看板 (Visual Dashboard)

你个人数字记忆的中央枢纽。进入专属的 **Cloud Viewer (云端面板)**，全维度检索你跨网页抓取过的每一次高亮、每一个标签和每一张图片。真正做到灵感再也不丢失。

<div align="center">
  <img src="https://chat-highlight.com/images/3.png" alt="Visual Dashboard" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 🔄 一键无损导出与同步 (One-Click Export & Sync)

借助安全的云同步机制在多端设备间无缝切换工作流。更喜欢完全本地化？只需一键，即可将结构化笔记格式化导出为 **Markdown、HTML 或 TXT**，完美保留对程序员至关重要的**代码块高亮与缩进格式**，轻松在 Notion 或 Obsidian 中建立你的第二大脑！

<div align="center">
  <img src="https://chat-highlight.com/images/4.png" alt="One-Click Export & Sync" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 🔒 本地优先的隐私保护 (Privacy-First)

你的数据完全属于你。默认情况下，你的每一次圈选和每一条笔记均安全地存放在你本机的浏览器硬盘中 (`chrome.storage.local`)。我们极其尊重隐私，确保即使是企业级的敏感架构代码也绝不会在未经你允许的情况下被传往第三方。

---

## 🎨 语义化的高亮色彩体系

我们内置了一套符合直觉的颜色分类系统，让批注本身就具备信息分类的职能：

| 颜色标记 | 专属类别 | 建议在 AI 对话中圈选的内容 |
| :--- | :--- | :--- |
| **🟡 黄色** | **核心重点** | AI 总结的关键思想、极其重要的架构决策或结论 |
| **🟢 绿色** | **代码/摘录** | **必须直接复用的代码片段 (Code Snippets)**、API 参数参考 |
| **🔵 蓝色** | **客观事实** | 值得作为论据的数据指标或文献出处 |
| **🔴 粉色** | **疑问待办** | 需要后续手动验证的错误日志、Bug 定位或追问点 |
| **🟣 紫色** | **灵感瞬间** | 突然迸发的脑洞、可以发散延展的野路子 |

---

## ⚔️ 当我们在拉踩竞品时，我们在比对什么？

我们向高亮插件领域的先驱致敬，但 Chat Highlight 是专门为了**知识生产者的输入管线**而设计的，跟它们完全不是一个物种。

| 核心特性 | Chat Highlight 🧠 | Glasp 🌍 | Web Highlight 🖍️ | Liner 🤖 |
| :--- | :---: | :---: | :---: | :---: |
| **AI 对话语义识别** | ✅ 独家机制 (Chat Note) | ❌ 不懂结构 | ❌ 不懂结构 | ❌ 不懂结构 |
| **代码格式保留度** | ✅ **100% 完美无损** | ⚠️ 降级为纯文本 | ⚠️ 降级为纯文本 | ⚠️ 降级为纯文本 |
| **对话大纲树状图** | ✅ 内置集成 | ❌ 无此设计 | ❌ 无此设计 | ⚠️ 基础能力 |
| **隐私权限优先级** | ✅ **默认本地存储** | ❌ 强制社交展现 | ⚠️ 强制上云 | ❌ 沦为 AI 追踪端 |
| **产品的最终归宿** | 纯粹私人的数据剪藏管道 | 做极客的社交网络 | 只是做了个网页涂鸦 | 转型成了重度对话 AI |

---

## 🚀 极速上手体验

1. 前往 [Chrome Web Store](https://chromewebstore.google.com/detail/chat-highlight-auto-chatg/ffnhgclfemimnnbkbhebjbobiipgkgbk?utm_source=item-share-cb) 下载安装插件。
2. 随手打开一个你的 ChatGPT 历史记录或 Gemini 聊天页。
3. 拖动鼠标选中文本（或代码块），当悬浮工具栏弹起时，选定你的颜色——专属的 AI 第二大脑，就此开启！

---

## 🤝 社区与支持

*   🐞 **遇到 Bug？** 别客气，请直接在仓库的 **Issues** 中发帖。
*   💡 **想加新功能？** 欢迎前往 **Discussions** 开启脑力激荡。
*   📚 **不知道怎么用？** 您可以畅读我们详尽的 [图文帮助文档](https://chat-highlight.com/docs.html)。
