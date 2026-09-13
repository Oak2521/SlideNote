<p align="center">
  <img src="https://gudong.s3.bitiful.net/images/slidenote-marquee-en.png" width="600" alt="SlideNote">
</p>

<h1 align="center">SlideNote</h1>

<p align="center">
  <strong>Slide notes, always by your side</strong><br>
  <strong>侧边笔记，常伴左右</strong><br>
  <a href="README.md">中文</a>
</p>

<p align="center">
  A sticky note in your browser sidebar — quick capture for fragments, never blocks content
</p>

<p align="center">
  <a href="https://github.com/maoruibin/SlideNote"><img alt="GitHub version" src="https://img.shields.io/badge/version-0.0.8.1-blue"></a>
  <a href="https://github.com/maoruibin/SlideNote/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/badge/license-MIT-green"></a>
  <a href="https://chromewebstore.google.com/detail/appaojacakbjbbellfehlgjophpdpjom"><img alt="Chrome Web Store" src="https://img.shields.io/badge/Chrome%20Web%20Store-Online-green"></a>
</p>

---

## ✨ Features

- **📌 Sidebar Panel, Never Blocks Content** — Lives in your browser sidebar, always accessible without covering your page
- **🔖 Web Clipper** — Right-click to save selected text from any webpage, aggregated by date
- **⚡️ Instant Access** — Opens in < 100ms, no app switching needed
- **🔄 Auto-Sync Across Devices** — Uses Chrome Storage API, your fragments follow you everywhere
- **🔍 Instant Search** — Real-time filter across all notes
- **📝 Markdown Support** — Basic formatting for keys, commands, and code
- **📌 Pin Notes** — Keep important notes at the top
- **💾 Auto-Save** — Saves automatically 1 second after you stop typing
- **⚡️ Ultra Lightweight** — No framework dependencies, only 57KB

---

## 🎯 Use Cases

| Use Case | Examples |
|----------|----------|
| Developers | Public documentation links, common commands, non-sensitive configuration |
| Multi-device Workers | Company Mac + Home Mac + Laptop — access the same fragments everywhere |
| Content Creators | Account credentials, content templates, prompts for AI tools |
| Daily Fragments | IP addresses, meeting notes, to-do lists, quick reminders |

**It's not a note-taking app.** Think of it as a cloud clipboard for the small pieces of information you need to access quickly while browsing.

---

## 📦 Installation

### Option 1: Chrome Web Store (Recommended)

<a href="https://chromewebstore.google.com/detail/appaojacakbjbbellfehlgjophpdpjom">
  <img src="https://storage.googleapis.com/web-dev-uploads/image/WbDnF6242M_4vTb4X3r3zgA7j10/WbDnF6242M_4vTb4X3r3zgA7j10_1714145428342.png" alt="Install from Chrome Web Store" width="200">
</a>

[Click here to install from Chrome Web Store](https://chromewebstore.google.com/detail/appaojacakbjbbellfehlgjophpdpjom)

### Option 2: Microsoft Edge Users

> SlideNote is fully compatible with Microsoft Edge (Edge 114+), but not yet published on Edge Add-ons store.

Edge users please install manually:

1. Download the latest release from [GitHub Releases](https://github.com/maoruibin/SlideNote/releases) and unzip
2. Open Edge browser
3. Go to `edge://extensions/`
4. Enable "Developer mode" in the bottom left
5. Click "Load unpacked"
6. Select the unzipped folder

### Option 3: Download Local Package

Download the latest release from [GitHub Releases](https://github.com/maoruibin/SlideNote/releases) and install manually:

1. Download and unzip the package
2. Open Chrome browser
3. Go to `chrome://extensions/`
4. Enable "Developer mode" in the top right
5. Click "Load unpacked"
6. Select the unzipped folder

### Option 4: Build from Source

```bash
# Clone the repository
git clone https://github.com/maoruibin/SlideNote.git
cd SlideNote

# Install dependencies
npm install

# Build for production
npm run build:prod
```

1. Open Chrome browser
2. Go to `chrome://extensions/`
3. Enable "Developer mode" in the top right
4. Click "Load unpacked"
5. Select the `dist` folder in the project directory

---

## 🚀 Usage

1. Click the SlideNote icon in your Chrome toolbar
2. The sidebar panel opens, ready to use
3. Click "New Note" to create your first note
4. Click a note to start editing
5. Right-click a note to reorder or delete
6. Auto-saves 1 second after you stop typing

---

## ❓ FAQ

### Where are notes stored? Is it secure?

SlideNote uses **Chrome Storage API** to store data:

- ✅ No third-party servers; data syncs directly between your local and Google
- ✅ Open source, code is transparent
- ✅ No personal information collected

### Is there a sync limit?

Chrome Storage Sync API has these limits:

- Total capacity ~100KB (about 50,000 Chinese characters)
- Suitable for: Non-sensitive commands, prompts, and similar fragmented information

SlideNote is a "sticky note", not a "notebook". For storing large amounts of content, consider using dedicated note apps like Notion or Obsidian.

---

## 🛠️ Tech Stack

```
Vanilla JS (ES6+)  →  No framework overhead
Vite               →  Fast build
Chrome Storage     →  Free cloud sync
CSS Variables      →  Design system
```

**Why no framework?**

| Reason | Description |
|--------|-------------|
| Performance | Load time < 100ms, no 100KB+ framework bloat |
| Simplicity | A fragment keeper doesn't need complex state management |
| Stability | No framework upgrade risks — code that works today still works years from now |

---

## 📁 Project Structure

```
slidenote/
├── src/sidepanel/
│   ├── core/           # Data layer (Store, EventBus, SyncManager)
│   ├── components/     # UI components
│   └── utils/          # Utility functions
├── docs/               # Documentation
└── public/icons/       # Icon resources
```

---

## 🎨 Design Philosophy

```
Restrained colors   →  Single-tone, non-distracting
Clear hierarchy     →  List vs content, at a glance
Comfortable spacing →  Room to breathe
Consistent rounded  →  Gentle, not sharp
```

---

## 🗺️ Roadmap

### v0.0.3 (Current)
- [x] Sidebar panel, never blocks content
- [x] Instant search & filter
- [x] Auto-save & cross-device sync
- [x] Basic Markdown support (preview mode)
- [x] Copy as rich text or Markdown source

### v0.0.4 (Planned)
- [ ] Data export (JSON/Markdown)
- [ ] Keyboard shortcuts
- [ ] Dark mode

---

## 📮 Follow the Author

<p align="center">
  Scan to follow my WeChat Official Account for development updates
</p>

<p align="center">
  <img src="https://blog.gudong.site/assets/profile/gongzhonghao.jpg" width="180" alt="WeChat QR">
</p>

---

## 💖 Support

If this project helps you, buy me a coffee ☕️

<table align="center">
  <tr>
    <td align="center">
      <img src="https://doc.gudong.site/assets/img/wechat-donate.5e615ccb.jpg" width="180" alt="WeChat Pay"/>
    </td>
    <td align="center">
      <img src="https://doc.gudong.site/assets/img/alipay-donate.7ec06101.jpg" width="180" alt="Alipay"/>
    </td>
  </tr>
</table>

---

## 🌟 More Works

Check out my other projects: **[doc.gudong.site](https://doc.gudong.site/)**

---

## 📄 License

[MIT License](LICENSE)

---

## 👨‍💻 Author

**Gudong** | Blog: https://blog.gudong.site/

> **Slide notes, always by your side**
> **侧边笔记，常伴左右**

---

If you find this project helpful, please give it a ⭐ Star!

## Storage boundary

SlideNote is a notes app, not a password or API-key vault. It uses Chrome storage local and sync paths; Chrome sync can transfer the corresponding data through Google to other devices. Do not describe it as local-only. Keep passwords, tokens and keys in a dedicated credential manager. This documentation clarification does not add an encrypted vault.
