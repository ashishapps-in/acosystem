# 🛠️ Acosystem — App Launcher Hub

> **All simple tools collected at one place.**  
> Free. Fast. Forever. Made by [Ashish Apps](https://ashish-apps.blogspot.com/).

---

## 🌐 Live Site

👉 **[ashishapps-in.github.io/acosystem](https://ashishapps-in.github.io/acosystem)**

---

## ✨ What is Acosystem?

Acosystem is a growing collection of **simple, lightweight web tools** — all free to use, no sign-up required, no ads, no nonsense. Every tool runs directly in your browser as a plain HTML file.

This repository will soon be home to **hundreds of tools** covering everything from productivity and utilities to games, calculators, converters, and more — all built and maintained by **Ashish Apps**.

---

## 🚀 Features

- **Zero installation** — open any tool directly in your browser
- **Fully offline-capable** — most tools work without an internet connection
- **Auto-discovering hub** — the launcher finds all tools automatically, no manual updates needed
- **Lightweight** — every tool is a single HTML file, no frameworks, no bloat
- **Unlimited free use** — no accounts, no paywalls, no limits

---

## 🧰 Tools Available

| Tool | Description | Status |
|------|-------------|--------|
| URL Shortener | Shorten long links using 25+ shorteners | ✅ Live |
| *(more tools coming soon...)* | | 🔧 Building |

> The launcher hub auto-detects every `.html` file added to this repo — so the list above grows automatically as new tools are published.

---

## 📁 How It Works

Each tool is a **standalone `.html` file** in the root of this repository. The `index.html` launcher reads the GitHub API, finds all HTML files, and displays them as cards — automatically, with no manual updates ever needed.

To add a new tool, just push a `.html` file with a `<title>` and `<meta name="description">` tag:

```html
<title>My Tool Name</title>
<meta name="description" content="What this tool does in one sentence.">
```

It will appear on the hub within minutes. That's it.

---

## 🏗️ Project Structure

```
acosystem/
├── index.html        ← The app launcher hub (auto-discovers all tools)
├── url.html          ← URL Shortener tool
├── [tool-name].html  ← Every new tool added here
└── README.md         ← You are here
```

---

## 🙌 About Ashish Apps

All tools in this collection are designed, built, and maintained by **Ashish Apps** — with a focus on simplicity, speed, and free access for everyone.

- 🌐 Blog: [ashish-apps.blogspot.com](https://ashish-apps.blogspot.com/)
- 💻 GitHub: [github.com/ashishapps-in](https://github.com/ashishapps-in)

---

## 📜 License

All tools are free to use for personal and non-commercial purposes.  
© Ashish Apps. All rights reserved.

---

<p align="center">
  Made with ❤️ by Ashish Apps &nbsp;·&nbsp; <em>Shalom</em>
</p>
