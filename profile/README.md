<div align="center">
  <picture>
    <img src="assets/readme/hero.svg" alt="Mythos - World Development Environment for Novelists" width="100%">
  </picture>
</div>

<p align="center">English · <a href="./README.TR.md">Türkçe</a></p>

**A writer's IDE for novelists building complex worlds.**

We're building a desktop app for fantasy, sci-fi, and epic fiction writers who outgrow generic note-taking tools and find traditional word processors too unstructured for series-length worldbuilding. Think: the structural discipline of Scrivener, merged with the contextual intelligence of a software IDE.

## 📦 Ecosystem

Mythos is built as a multi-repository ecosystem to separate concerns between the core engine, the user interface, and our documentation.

- [`mythoside-core`](https://github.com/Mythos-IDE/mythoside-core)  
  The core engine, knowledge graph manager, and local SQLite server. Built in **Rust**.
- [`mythoside-ts`](https://github.com/Mythos-IDE/mythoside-ts)  
  The desktop application and user interface. Built with **Tauri**, **React**, and **TypeScript**.
- [`mythoside-website`](https://github.com/Mythos-IDE/mythoside-website)  
  The official landing page and documentation. Built with **Vite** and **React**.

## 🧠 Core Philosophy

- 📚 **Built for fiction, not notes** — a Series → Book → Chapter → Scene hierarchy that's built in, not something you configure yourself.
- 🔗 **Contextual world-building** — type `@CharacterName` and get an instant profile card without leaving your draft.
- 💾 **Local-first, always** — plain Markdown + YAML frontmatter is the real source of truth. Your novel isn't held hostage by a server.
- ⚡ **Fast** — a local SQLite (FTS5) index makes cross-referencing instant.

## 🤝 Get Involved

Early development. Follow along, star the repositories, or jump into [Discussions](https://github.com/Mythos-IDE/mythoside-core/discussions) if you're building epic-length fiction and want a say in how this shapes up.

- **Issues & feature ideas** → [Core Issues](https://github.com/Mythos-IDE/mythoside-core/issues) | [TS Issues](https://github.com/Mythos-IDE/mythoside-ts/issues)
- **General questions** → [Discussions](https://github.com/Mythos-IDE/mythoside-core/discussions)
- **Security reports** → security@mythoside.com
- **Everything else** → hello@mythoside.com

---
<div align="center">
  <sub>Open Source software by the Mythos Team.</sub>
</div>
