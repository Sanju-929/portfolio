# Responsive Multilingual Portfolio Website 🌐 👨‍💻

Welcome to my personal portfolio repository! This website is built using **Tailwind CSS** and features a modern **Bento Grid** layout, interactive fluid animations, full **Dark Mode ("Obsidian Noir")** support, and native bilingual folder separation.

## 🔗 Live Demo
Since this is hosted as a GitHub Project Page, you can access the localized live deployments directly using the links below:
* 🇬🇧 **English Version:** [https://Sanju-929.github.io/portfolio/en/index.html](https://Sanju-929.github.io/portfolio/en/index.html)
* 🇩🇪 **German Version:** [https://Sanju-929.github.io/portfolio/de/index.html](https://Sanju-929.github.io/portfolio/de/index.html)

---

## 📂 Project Structure
The repository features an automatic language detection entry point at the root level that dynamically channels incoming browser request payloads without third-party dependencies:

```text
portfolio/
├── index.html        (Root Multi-Routing / Auto-Language Detection Script)
├── favicon.ico       (Custom SV Brand Token Identity Asset)
├── en/
│   └── index.html    (English Production Build - Tailwind CSS & Bento Grid)
└── de/
    └── index.html    (German Production Build - Tailwind CSS & Bento Grid)
