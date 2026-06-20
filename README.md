# 📝 MarkPad — Online Markdown Editor

A lightweight Markdown editor with **live preview** that runs 100% in your browser. No login, no server, no install. Type on the left, see the result on the right instantly.

🔗 **Live demo:** [markpad-markdown.netlify.app](https://markpad-markdown.netlify.app/)

---

## ✨ Features

- ⚡ **Real-time live preview** — see results as you type
- 🧰 **Full toolbar** — headings, bold, italic, lists, checklists, quotes, links, images, code, tables
- 💾 **Auto-save** — your work is saved in the browser (localStorage), survives refresh
- ⬇️ **Export** — download as `.md` or `.html` (ready to share)
- 📋 **Copy HTML** — copy the rendered HTML to clipboard with one click
- 🌙 **Dark & light mode**
- ⌨️ **Keyboard shortcuts** — `Ctrl/Cmd + B` (bold), `Ctrl/Cmd + I` (italic)
- 📊 **Statistics** — word, character, and line count
- 📱 **Responsive** — works great on both mobile and desktop
- 🚀 **Zero dependencies** — custom-built Markdown parser, runs fully offline

---

## 🖱️ How to Use

1. Open [markpad-markdown.netlify.app](https://markpad-markdown.netlify.app/)
2. Start typing in the **Editor** panel (left)
3. See the rendered output in the **Preview** panel (right)
4. Use the **toolbar** for quick formatting, or type manually:

| Goal | Type | Result |
|---|---|---|
| Heading | `# Title` | Large heading |
| Bold | `**text**` | **text** |
| Italic | `*text*` | *text* |
| Strikethrough | `~~text~~` | ~~text~~ |
| List | `- item` | • item |
| Checklist | `- [x] done` | ☑ done |
| Quote | `> quote` | ❝ quote |
| Link | `[text](url)` | link |
| Code | `` `code` `` | `code` |

5. Done? Click **⬇ .md** / **⬇ .html** to download, or **Copy HTML**.

> 💡 Your text auto-saves in the browser — safe on refresh. Click **Clear** to start fresh, or **Sample** to see a format demo.

---

## 🛠️ Tech Stack

- Pure HTML, CSS & JavaScript (vanilla) — **no frameworks or libraries**
- Custom-built Markdown parser
- Persistence via `localStorage`

---

## 🚀 Run Locally

No build step needed — just open the file:

```bash
git clone https://github.com/vhmns14/markpad.git
cd markpad
# open index.html in your browser (double-click), or:
open index.html        # macOS
# xdg-open index.html  # Linux
# start index.html     # Windows
