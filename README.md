<div align="center">

[简体中文](./README_zh.md) | English

</div>

# 🧠 Chat Highlight: The Ultimate AI Chat Highlighter & Exporter

<div align="center">

[![Chrome Web Store](https://img.shields.io/badge/Available_on-Chrome_Web_Store-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/chat-highlight-auto-chatg/ffnhgclfemimnnbkbhebjbobiipgkgbk?utm_source=github&utm_medium=readme&utm_campaign=repo_launch) [![Chrome Web Store Rating](https://img.shields.io/chrome-web-store/rating/ffnhgclfemimnnbkbhebjbobiipgkgbk?label=rating&style=for-the-badge&color=ffd000)](https://chromewebstore.google.com/detail/chat-highlight-auto-chatg/ffnhgclfemimnnbkbhebjbobiipgkgbk?utm_source=github&utm_medium=readme&utm_campaign=repo_launch) [![Official Docs](https://img.shields.io/badge/Official-Documentation-blue?style=for-the-badge)](https://chat-highlight.com/docs.html) [![Homepage](https://img.shields.io/badge/Visit-chat--highlight.com-success?style=for-the-badge)](https://chat-highlight.com/)

</div>

**Stop copy-pasting your AI conversations.** 

Chat Highlight is an AI-native browser extension that automatically structures, highlights, and exports your **ChatGPT** and **Gemini** conversations into flawless Markdown. 

<div align="center">
  <img src="https://chat-highlight.com/images/og-share.png" alt="Chat Highlight Banner" width="100%" style="border-radius: 8px;">
</div>

<br>

## 🎥 See It in Action (Demo)

<div align="center">

[![Chat Highlight 1-Minute Demo](https://img.youtube.com/vi/ehp6oAzvA00/hqdefault.jpg)](https://www.youtube.com/watch?v=ehp6oAzvA00)

</div>

> [!NOTE]
> 💡 **Notice on Open Source:** This repository serves as our official **Community Hub** for Issue Tracking, Feature Requests, and Public Roadmap. 
> To protect our core DOM-parsing engine and Cloud Viewer infrastructure, the extension itself is **closed-source**. However, we enforce a strict **Local-First** philosophy — your private research never leaves your browser unless you explicitly enable cloud sync!

---

## 🔥 Why Chat Highlight? (The Pain We Solve)

Are you a developer, researcher, or power user? You probably know the pain:

| ❌ The Problem | highly inefficient AI workflows |
| :--- | :--- |
| **Lost Context** | Losing a brilliant architectural design from a ChatGPT session weeks ago. |
| **Broken Code** | Copy-pasting AI code blocks only to find formatting and syntax highlighting broken. |
| **Needle in a Haystack** | Navigating through a 50-turn conversation trying to find one specific prompt. |

✅ **Chat Highlight solves all of this by building a dedicated Data Pipeline between your AI chats and your Second Brain (Notion/Obsidian).**

---

## 🎯 Workflow: Web to Knowledge Base

Working with Chat Highlight is seamless:

| 🌐 Browse | 🖱️ Select | 🎨 Highlight | 📝 Organize | ☁️ Sync & Export |
| :---: | :---: | :---: | :---: | :---: |
| Read AI Chats | Select Text/Code | Pick a Category | Add Tags/Notes | To Cloud/Notion |

---

## ✨ Core Features

### 🤖 Auto-highlight AI Chats

Stop manual copying. Chat Highlight automatically detects conversation structures in **ChatGPT and Gemini**, separating your "Prompts" from AI "Answers" to turn fleeting chats into permanent, highlighted notes.

<div align="center">
  <img src="https://chat-highlight.com/images/1.png" alt="Auto-highlight AI Chats" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 🌲 Structured Sidebar & TOC

Forget scrolling through miles of chat history. Manage your insights in a hierarchical **Tree View** designed for clarity. Filter by tags, jump to specific prompts, and edit notes directly in the sidebar without losing context.

<div align="center">
  <img src="https://chat-highlight.com/images/2.png" alt="Structured Sidebar" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 📊 Visual Cloud Dashboard

A centralized hub for your digital memory. Access your personal **Cloud Viewer** to search every highlight, tag, and image you have ever saved across the web. Never lose a valuable insight again.

<div align="center">
  <img src="https://chat-highlight.com/images/3.png" alt="Visual Dashboard" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 🔄 One-Click Export & Preserved Code Syntax

Switch seamlessly between your laptop and desktop with our secure Cloud Sync. Prefer local? Export your structured notes to **Markdown, HTML, or TXT** in one click to build your second brain in Notion or Obsidian while **100% preserving your code block syntax highlighting**!

<div align="center">
  <img src="https://chat-highlight.com/images/4.png" alt="One-Click Export & Sync" width="85%" style="border-radius: 8px; border: 1px solid #e2e8f0; margin-top: 10px; margin-bottom: 20px;">
</div>

### 🔒 Privacy-First Architecture

Your data belongs to you. By default, every highlight and note is securely stored in your browser's local storage (`chrome.storage.local`). We employ a zero-knowledge architecture to ensure your sensitive enterprise code or research stays completely private unless you explicitly opt into Cloud Sync.

---

## 🎨 Highlight Legend

Customize your knowledge base using our color-coded semantic categories:

| Color | Category | Best Use Case for AI Chats |
| :--- | :--- | :--- |
| **🟡 Yellow** | **Important** | Key takeaways, ultimate conclusions or architectural decisions |
| **🟢 Green** | **Excerpt** | **Code Snippets**, formulas, API references, or quotes |
| **🔵 Blue** | **Fact** | Verifiable data points or objective facts |
| **🔴 Pink** | **Question** | Follow-up questions, errors to debug, stuff to verify |
| **🟣 Purple** | **Inspiration** | Brainstorming ideas, "Aha!" moments |

---

## ⚔️ Chat Highlight vs Traditional Tools

We respect the pioneers, but Chat Highlight is built for a completely different workflow. We are a **productivity pipeline**, not just a reading tool.

| Feature | Chat Highlight 🧠 | Glasp 🌍 | Web Highlight 🖍️ | Liner 🤖 |
| :--- | :---: | :---: | :---: | :---: |
| **AI Dialog Parsing** | ✅ Yes (Chat Note Mode) | ❌ No | ❌ No | ❌ No |
| **Code Highlighting** | ✅ **100% Preserved** | ⚠️ Text only | ⚠️ Text only | ⚠️ Text only |
| **Tree-View TOC** | ✅ Built-in | ❌ No | ❌ No | ⚠️ Basic |
| **Privacy Default** | ✅ **Local storage** | ❌ Social Feed | ⚠️ Cloud forced | ❌ AI tracked |
| **Core Goal** | Private Data Pipeline | Social Sharing | Simple Marking | AI Assistant |

---

## 🚀 Get Started in 3 Steps

1. Install from the [Chrome Web Store](https://chromewebstore.google.com/detail/chat-highlight-auto-chatg/ffnhgclfemimnnbkbhebjbobiipgkgbk?utm_source=item-share-cb).
2. Open any ChatGPT or Gemini conversation.
3. Select any text or code block. When the floating toolbar appears, pick a color to start building your AI Second Brain!

---

## 🤝 Community & Support

*   🐞 **Found a bug?** Please open an **Issue** in this repository.
*   💡 **Have a feature idea?** Share it in our **Discussions** tab.
*   📚 **Need help?** Check out the comprehensive [Documentation](https://chat-highlight.com/docs.html).
