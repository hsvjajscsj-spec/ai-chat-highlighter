<p align="center">
  <a href="./README_zh.md">简体中文</a> | English
</p>

<h1 align="center">Chat Highlight</h1>

<p align="center">
  <strong>AI Chat Highlighter for ChatGPT, Claude, and Gemini</strong>
</p>

<p align="center">
  Save useful AI answers as structured notes. Export to Markdown, HTML, TXT, or Notion.
</p>

<p align="center">
  <a href="https://chromewebstore.google.com/detail/chat-highlight-auto-chatg/ffnhgclfemimnnbkbhebjbobiipgkgbk?utm_source=github&utm_medium=readme&utm_campaign=repo_launch"><img alt="Chrome Web Store" src="https://img.shields.io/badge/Chrome%20Web%20Store-Install-4285F4?logo=googlechrome&logoColor=white"></a>
  <a href="https://chromewebstore.google.com/detail/chat-highlight-auto-chatg/ffnhgclfemimnnbkbhebjbobiipgkgbk?utm_source=github&utm_medium=readme&utm_campaign=repo_launch"><img alt="Chrome Web Store rating" src="https://img.shields.io/chrome-web-store/rating/ffnhgclfemimnnbkbhebjbobiipgkgbk?label=rating&color=ffd000"></a>
  <a href="https://chat-highlight.com/docs.html"><img alt="Documentation" src="https://img.shields.io/badge/Docs-User%20Guide-blue"></a>
  <a href="https://chat-highlight.com/"><img alt="Homepage" src="https://img.shields.io/badge/Website-chat--highlight.com-success"></a>
</p>

Chat Highlight is a local-first Chrome extension for highlighting, structuring, and exporting conversations from **ChatGPT**, **Claude**, and **Gemini**. Capture prompts, answers, code snippets, notes, images, and tags, then export to **Markdown**, **HTML**, **TXT**, or directly to **Notion**.

<div align="center">
  <img src="https://chat-highlight.com/images/og-share.png" alt="Chat Highlight AI chat highlighter banner" width="100%" style="border-radius: 8px;">
</div>

<br>

## 🎥 Demo

<div align="center">

[![Chat Highlight demo video](https://img.youtube.com/vi/ehp6oAzvA00/hqdefault.jpg)](https://www.youtube.com/watch?v=ehp6oAzvA00)

</div>

> [!NOTE]
> **Repository status:** This repository is the official community hub for issue tracking, feature requests, documentation links, and public roadmap notes.
> The extension code is currently closed-source to protect the core DOM parsing and cloud sync infrastructure. The product itself is built around a **local-first** model: your highlights and notes stay in browser storage unless you choose to enable cloud sync.

---

## 🔥 Why Chat Highlight?

AI chats are now part research notebook, part coding session, part brainstorming room. The problem is that useful answers are easy to lose.

| Problem | What happens without a dedicated AI chat highlighter |
| :--- | :--- |
| ❌ Lost context | A useful ChatGPT, Claude, or Gemini answer gets buried in a long conversation. |
| ❌ Broken code formatting | Copy-pasted code blocks lose indentation, language context, or readable structure. |
| ❌ Endless scrolling | Finding one prompt inside a 50-turn AI research session becomes manual archaeology. |
| ❌ Scattered notes | Highlights, tags, images, and follow-up notes end up across multiple tools. |

**Chat Highlight turns long AI conversations into structured, searchable knowledge cards that you can keep locally, sync across devices, or export to Notion.**

---

## 🎯 Workflow

| 🌐 Read | 🎨 Highlight | 🌲 Structure | 🔎 Search | 📤 Export |
| :---: | :---: | :---: | :---: | :---: |
| Open ChatGPT, Claude, Gemini, or any webpage | Select text, code, or images | Separate prompts, answers, notes, and tags | Use Sidebar or Cloud Dashboard | Markdown, HTML, TXT, or Notion |

---

## ✨ Core Features

### 🤖 AI-Native Chat Highlighting

Chat Highlight recognizes supported AI chat page structure across **ChatGPT**, **Claude**, and **Gemini**. It helps separate your prompts from AI answers so a messy conversation becomes a clean outline.

<div align="center">
  <img src="https://chat-highlight.com/images/1.png" alt="Auto-highlight AI chats in ChatGPT Claude Gemini" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 🌲 Tree View Sidebar and Live TOC

Use a hierarchical sidebar to navigate long conversations, filter by tag, jump to specific prompts, and edit notes without losing your place.

<div align="center">
  <img src="https://chat-highlight.com/images/2.png" alt="Structured sidebar and live table of contents" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 📊 Cloud Dashboard

Search highlights, tags, images, and saved pages in one visual dashboard. Free users can keep local highlights and limited cloud backup; paid plans unlock more cloud sync capacity and dashboard history.

<div align="center">
  <img src="https://chat-highlight.com/images/3.png" alt="Cloud Dashboard for AI conversation highlights" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 📤 Export to Markdown, HTML, TXT, and Notion

Export structured notes locally as **Markdown**, **HTML**, or **TXT**, or send highlights directly to **Notion**. HTML export is designed to preserve the visual structure of AI chat content, including readable code blocks.

<div align="center">
  <img src="https://chat-highlight.com/images/4.png" alt="Export AI chats to Markdown HTML TXT and Notion" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 🔒 Local-First Privacy

By default, highlights, notes, tags, and page data are stored in your browser via `chrome.storage.local`. Cloud sync is optional. We do not use your private notes to train AI models.

---

## 🎨 Highlight Categories

| Color | Category | Good for |
| :--- | :--- | :--- |
| 🟡 Yellow | **Important** | Key takeaways, decisions, final answers |
| 🟢 Green | **Excerpt** | Code snippets, API references, reusable text |
| 🔵 Blue | **Fact** | Evidence, data points, citations |
| 🔴 Pink | **Question** | Follow-ups, bugs, unresolved issues |
| 🟣 Purple | **Inspiration** | Ideas, brainstorming, creative sparks |

---

## ⚔️ Chat Highlight vs Traditional Highlighters

| Feature | Chat Highlight | Generic web highlighters |
| :--- | :---: | :---: |
| AI chat structure detection | ✅ Yes | ❌ Usually no |
| Prompt / answer organization | ✅ Yes | ❌ No |
| Tree View and Live TOC | ✅ Yes | ⚠️ Rarely |
| Code-friendly export | ✅ Yes | ⚠️ Often plain text only |
| Local-first storage | ✅ Yes | ⚠️ Varies |
| Direct Notion export | ✅ Yes | ⚠️ Varies |

---

## 🚀 Install

1. Install Chat Highlight from the [Chrome Web Store](https://chromewebstore.google.com/detail/chat-highlight-auto-chatg/ffnhgclfemimnnbkbhebjbobiipgkgbk?utm_source=github&utm_medium=readme&utm_campaign=repo_launch).
2. Open a ChatGPT, Claude, Gemini, or regular webpage.
3. Select text, code, or an image.
4. Highlight, tag, add notes, and export when ready.

---

## 🤝 Community and Support

- Found a bug? Open an [Issue](../../issues).
- Have a feature idea? Open a [feature request](../../issues/new).
- Need help? Read the [official documentation](https://chat-highlight.com/docs.html).
