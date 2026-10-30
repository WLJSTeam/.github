# WLJS

*Open, web-native, accesible tools for computational research*

We build **WLJS Notebook** and its surrounding open-source ecosystem: a modern open-source environment for Wolfram Language and its open-source implementations, interactive visualization, scientific applications, presentations, and web publishing.

WLJS combines typeset mathematical input, live controls, JavaScript integration, portable interactive output, and a plain-text notebook format that works naturally with Git.

[Website](https://wljs.io/) ·
[How to Install](https://wljs.io/frontend/setup) ·
[Documentation](https://wljs.io/frontend/Overview) ·
[Discussions](https://github.com/WLJSTeam/wljs-notebook/discussions) ·
[Support the project](https://opencollective.com/wljs-notebook)

## Our projects

- **[WLJS Notebook](https://github.com/WLJSTeam/wljs-notebook)** — the open-source notebook interface for Wolfram Language (or Wolfram Engine).
- **[Web Components](https://github.com/WLJSTeam/web-components)** — tools for embedding interactive WLJS notebooks in ordinary web pages.
- **[Web Components MDX](https://github.com/WLJSTeam/web-components-mdx)** — an MDX and Next.js template for publishing interactive computational content.
- **Infrastructure libraries** — networking, HTTP, socket, and runtime components supporting the wider WLJS ecosystem.

## Why WLJS?

WLJS is designed for researchers, educators, students, and developers who want to:

- create interactive notebooks and scientific tools;
- keep their work local and available **offline**;
- version notebooks using Git;
- combine Wolfram Language with JavaScript and any web libraries;
- build interactive presentations and reports;
- publish notebooks as portable HTML (offline and a single file bundle) or MDX;
- work with notebooks through a CLI or Model Context Protocol server.

Everything is task-driven and is carefully tested and refined in real experiments with physicist from University of Augsburg 🇩🇪

## Get started

1. Install Wolfram Engine or use an available Wolfram Kernel.
2. [Download WLJS Notebook](https://wljs.io/frontend/setup).
3. Create a notebook and evaluate your first expression:

```wl
Manipulate[
  Plot[Sin[n x], {x, 0, 2 Pi}],
  {n, 1, 10}
]
```

WLJS Notebook runs on Windows, macOS, GNU/Linux with native extensions, Docker, and remote servers.


## Community

- [GitHub Discussions](https://github.com/WLJSTeam/wljs-notebook/discussions)
- [Reddit](https://www.reddit.com/r/wljs/)
- [Telegram](https://t.me/wljs_support)
- [WLJS website and blog](https://wljs.io/)

## Support WLJS

WLJS is an independent open-source project. Donations help cover code signing, infrastructure, testing, and other recurring project costs.

[Support WLJS through Open Collective →](https://opencollective.com/wljs-notebook)

---

WLJS Notebook is licensed under the **GNU Affero General Public License v3**.

WLJS is an independent project and is not affiliated with, endorsed by, or sponsored by Wolfram Research.
