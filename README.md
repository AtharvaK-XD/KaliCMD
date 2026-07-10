# KaliCMD ⚔️

> **256 Kali Linux commands. One page. Zero fluff.**

A clean, fast A–Z reference for Kali Linux commands — built entirely in HTML, CSS, and vanilla JavaScript. No frameworks. No dependencies. Just pure utility.

🔗 **Live Site → [kalicmd.netlify.app](https://kalicmd.netlify.app/)**

---

## What It Does

KaliCMD indexes **256 Kali Linux commands** across **24 letters**, giving you:

- 🔍 **Instant search** — press `/` to focus the search bar and filter commands in real time
- 📋 **One-click copy** — copy any command to clipboard instantly
- 🗂️ **A–Z browsing** — expand/collapse sections by letter
- ⚡ **Zero load time** — pure HTML, no build step, no JS bundle

---

## Tech Stack

| Layer | Choice |
|-------|--------|
| Markup | HTML5 |
| Styling | CSS3 |
| Logic | Vanilla JavaScript |
| Hosting | Netlify |

---

## Project Structure

```
kalicmd/
├── index.html       # Everything lives here — markup, styles, and scripts
└── README.md
```

---

## Running Locally

No setup required. Just clone and open:

```bash
git clone https://github.com/<your-username>/kalicmd.git
cd kalicmd
open index.html      # or just drag it into your browser
```

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `/` | Focus search |
| `Esc` | Clear search |

---

## Deploying

The project is hosted on **Netlify** via drag-and-drop or Git integration. To deploy your own fork:

1. Push to GitHub
2. Connect the repo on [netlify.com](https://netlify.com)
3. Set publish directory to `/` (root)
4. Deploy ✅

---

## Contributing

Found a missing command? Wrong description? PRs are welcome.

1. Fork the repo
2. Add/fix the command entry in `index.html`
3. Open a pull request with a brief description

---

<p align="center">Made for pentesters, students, and anyone who keeps forgetting flags.</p>
