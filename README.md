# 🛠️ Acosystem — App Launcher Hub

> **Simple browser tools collected in one place.**
> Free. Fast. Lightweight. Made by [Ashish Apps](https://ashish-apps.blogspot.com/).

---

## 🌐 Live Site

👉 **[ashishapps-in.github.io/acosystem](https://ashishapps-in.github.io/acosystem)**

---

## ✨ What is Acosystem?

Acosystem is a growing collection of standalone web tools that run directly in the browser. Each app is kept as a plain HTML file so it is easy to open, share, host on GitHub Pages, and improve without a heavy build pipeline.

The goal is simple: useful tools with no sign-up, no installation, and minimal friction.

---

## 🚀 Features

- **Zero installation** — open the launcher or any tool directly in your browser.
- **Standalone tools** — every app lives in a single `.html` file.
- **Searchable launcher** — the hub helps users find tools quickly.
- **Lightweight hosting** — designed for GitHub Pages and static hosting.
- **Consistent metadata** — every tool includes a title and description for discovery.
- **Free access** — no accounts, subscriptions, or paywalls.

---

## 🧰 Tools Available

| Tool | File | Description | Status |
|------|------|-------------|--------|
| App Launcher | `index.html` | Search and open every tool from a central hub. | ✅ Live |
| URL Shortener | `url.html` | Shorten links, compare providers, and generate QR codes. | ✅ Live |
| CalcTech | `cal.html` | Calculator with history, precision controls, themes, and settings. | ✅ Live |
| Ashish Dictionary | `dictionary.html` | Search definitions, examples, and vocabulary helpers. | ✅ Live |
| Ashish News | `news.html` | Browse, filter, save, and manage personalized news stories. | ✅ Live |
| AcoShare | `file.html` | Transfer files directly between browsers with peer-to-peer sharing. | ✅ Live |
| Connect the Lines | `Connect P2P.html` | Play a real-time peer-to-peer line-connection game with friends. | ✅ Live |

---

## 📁 How It Works

Each tool is a standalone `.html` file in the root of this repository. The launcher can discover HTML files, read their `<title>` and `<meta name="description">` tags, and display them as cards.

To add a new tool, create a new `.html` file with at least:

```html
<title>My Tool Name</title>
<meta name="description" content="What this tool does in one sentence.">
```

Then open the tool directly or publish it through the launcher.

---

## 🏗️ Project Structure

```text
acosystem/
├── index.html          ← App launcher hub
├── url.html            ← URL shortener and QR tool
├── cal.html            ← Calculator
├── dictionary.html     ← Dictionary
├── news.html           ← News hub
├── file.html           ← P2P file transfer
├── Connect P2P.html    ← P2P game
└── README.md           ← Project documentation
```

---

## ✅ Maintenance Checklist

When adding or revising tools:

1. Keep the app usable as a single HTML file.
2. Include a clear `<title>` and `<meta name="description">`.
3. Test the tool in a browser after editing.
4. Prefer accessible labels, responsive layouts, and readable contrast.
5. Avoid adding unnecessary build steps or large dependencies.

---

## 🙌 About Ashish Apps

All tools in this collection are designed, built, and maintained by **Ashish Apps** with a focus on simplicity, speed, and free access for everyone.

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
