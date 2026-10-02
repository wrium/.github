<div align="center">

# Wrium

**Full reactivity with minimal code size.**

A minimalist JavaScript library for building reactive user interfaces with declarative HTML templates, zero dependencies, and no build step required.

[🌐 Website (wrium.dev)](https://wrium.dev) • [📖 Documentation](https://wrium.dev/docs/introduction.html) • [📦 npm Packages](https://www.npmjs.com/org/wrium) • [💬 GitHub](https://github.com/wrium)

[![npm version](https://img.shields.io/npm/v/@wrium/wrium.svg?color=38bdf8&label=npm%20@wrium/wrium)](https://www.npmjs.com/package/@wrium/wrium)
[![Bundle Size](https://img.shields.io/badge/bundle%20size-~10.9%20KB-10b981)](https://wrium.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

</div>

---

## ✨ Overview

**Wrium** brings the elegance and ergonomics of modern reactive frameworks directly to your browser without the ceremony. No bundler, no virtual DOM overhead, and no build configuration to wrestle with — drop in a script tag or install via npm, write your HTML templates, and let Wrium handle DOM updates with fine-grained reactivity.

* ⚡ **Zero Build Step Required**: Works right out of the box in plain HTML with native ES modules.
* 🔮 **Full Reactivity System**: Automatic dependency tracking powered by `ref()`, `reactive()`, `computed()`, and `watchEffect()`, batched on microtasks for optimal performance.
* 📝 **Declarative Templates**: Intuitive directives (`v-if`, `v-for`, `v-model`, `v-show`, `v-text`) and shorthand bindings (`@click`, `:class`, `:style`) that read your DOM directly.
* 🧩 **Modular Components**: Define reusable UI components with reactive props via `app.component()` without JSX or compilation.
* 🔌 **Pluggable Architecture**: Built-in and third-party directives use the exact same extensible registry.
* 🪶 **Ultra-Lightweight**: Only **~10.9 KB** minified for the complete core.
* 🛡️ **TypeScript Ready**: Ships with native, fully-typed `.d.ts` declaration files with proper generics (`ref<T>`, `computed<T>`).


## 📦 The Wrium Ecosystem

The Wrium organization maintains the core framework alongside official tools, documentation, and plugins:

| Repository / Package | Description | Status |
| :--- | :--- | :---: |
| [**`wrium`**](https://github.com/wrium/wrium) <br> `@wrium/wrium` | The core reactive UI library, declarative template compiler, and component engine. | [![npm](https://img.shields.io/npm/v/@wrium/wrium.svg)](https://www.npmjs.com/package/@wrium/wrium) |
| [**`wrium-evasive-button`**](https://github.com/wrium/wrium-evasive-button) <br> `@wrium/evasive-button` | Playful runaway button directive (`v-evade`) with wall-sliding physics, radius leashing, and form completion triggers. | Ready v1.0.0 |
| [**`wrium-password-strength`**](https://github.com/wrium/wrium-password-strength) <br> `@wrium/password-strength` | Real-time interactive password evaluation directive and security scoring. | Ready v1.0.0 |
| [**`wrium-site`**](https://github.com/wrium/wrium-site) | The official documentation site and interactive playground running at [wrium.dev](https://wrium.dev). | Live |

---

## 🌐 Documentation & Resources

* 📖 **Official Website & Docs**: [wrium.dev](https://wrium.dev)
* 📚 **Getting Started Guide**: [wrium.dev/docs/introduction.html](https://wrium.dev/docs/introduction.html)
* 💡 **Interactive Playground**: Explore live demos and examples on [wrium.dev](https://wrium.dev)
* 🐞 **Report Issues**: [github.com/wrium/wrium/issues](https://github.com/wrium/wrium/issues)
* 🤝 **Contributing**: Contributions, feedback, and plugin ideas are warmly welcome across all repositories!

---

<div align="center">
  <sub>Crafted with passion for minimalist web craftsmanship. Released under the <a href="https://opensource.org/licenses/MIT">MIT License</a>.</sub>
</div>
