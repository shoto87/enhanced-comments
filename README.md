# **Enhanced Comments – Markit**

✨ _Make your code comments meaningful, colorful, and easy to read._

![Enhanced Comments Demo](images/demo.gif) <!-- Replace with actual gif or screenshot -->

---

## 📌 Overview

**Markit** helps you turn plain, boring comments into **color-coded, meaningful annotations** that stand out in your code.  
No more skimming past important TODOs, FIXMEs, or warnings — each type of comment gets its own **distinct and aesthetic color**.

---

## 🎯 Features

- 🎨 **Beautiful Color Coding** for:

  - ✅ Normal comments → subtle highlighted green
  - 🐛 Bugs → bold red (warning-style)
  - 🚀 Improvements / Enhancements → bright blue
  - ❓ Questions → modern purple
  - ⚠️ Warnings → amber/yellow
  - 📌 Highlights → vibrant cyan
  - 🗑 Deprecated → muted gray

- 🖌 Works with your existing theme — only comments get recolored.
- ⚡ Lightweight and fast — activates only for supported languages.
- 🔧 Fully customizable in `settings.json`.

---

## 🖋 Comment Syntax Guide

Markit uses **special prefixes** in comments to determine the style:

| Prefix | Meaning              | Example                              |
| ------ | -------------------- | ------------------------------------ |
| `//%`  | **Bug / Issue**      | `//% This function fails on null`    |
| `//!`  | **Error / Critical** | `//! Do not remove this validation`  |
| `//+`  | **Improve / TODO**   | `//+ Refactor this algorithm`        |
| `//?`  | **Question**         | `//? Why is this loop O(n^2)?`       |
| `//*`  | **Highlight**        | `//* Key business logic starts here` |
| `//~`  | **Deprecated**       | `//~ Old API method - do not use`    |
| `//`   | **Normal Comment**   | `// This is a normal note`           |

---

## 🖼 Example

```javascript
// This is a normal comment
//% This function fails on null input
//! This will crash if user is not logged in
//+ Refactor this for better performance
//? Should we cache the result?
//* Important: This section handles authentication
//~ Legacy code - will be removed in v2
```

With **Markit**, these will appear in **different, modern colors** — easy to scan at a glance.

---

## 📂 Supported Languages

- JavaScript / TypeScript
- Python
- C / C++
- Java
- And more — configurable in `package.json`

---

## ⚙ Installation

1. Open **VS Code**.
2. Go to **Extensions** (`Ctrl+Shift+X` / `Cmd+Shift+X` on Mac).
3. Search for **Markit** or **Enhanced Comments**.
4. Click **Install** and reload VS Code.

---

## 🛠 Configuration

If you want to customize colors:

1. Open **Command Palette** (`Ctrl+Shift+P` / `Cmd+Shift+P`)
2. Search for **Preferences: Open Settings (JSON)**
3. Add your preferred colors under `editor.tokenColorCustomizations`.

Example:

```json
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "scope": "comment.enhancer.bug",
      "settings": { "foreground": "#FF5F56" }
    },
    {
      "scope": "comment.enhancer.improve",
      "settings": { "foreground": "#61AFEF" }
    }
  ]
}
```

---

## 🚀 Performance Note

Markit now activates **only for supported languages** to keep VS Code fast and responsive.

---

## 🧑‍💻 Contributing

Want a new feature or language support?

- Fork the repo
- Create a branch
- Submit a Pull Request

---

## 📜 License

MIT License — free to use, modify, and share.

---

## ❤️ Support This Project

If you enjoy Markit, consider **starring the repo** ⭐ and leaving a review in the Marketplace.
