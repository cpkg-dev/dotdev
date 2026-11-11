# cpkg dotdev

This is the official website github repo.
If you wanna help out with fixing issues, translations or whatever else feel free to.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `bun install`             | Installs dependencies                            |
| `bun dev`             | Starts local dev server at `localhost:4321`      |
| `bun build`           | Build your production site to `./dist/`          |
| `bun preview`         | Preview your build locally, before deploying     |
| `bun astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `bun astro -- --help` | Get help using the Astro CLI                     |

[astrojs our documentation](https://docs.astro.build).

## Hostnames & Services

| Hostname | Purpose & Target |
| :--- | :--- |
| `cpkg.dev` | **Landing Page & Overview:** Minimalist splash page, installation one-liner, and quick-start guide. |
| `registry.cpkg.dev` | **Package Registry & Index:** The central index for package resolution, manifest search, and pre-built binaries. |
| `docs.cpkg.dev` | **Developer Documentation:** API reference for `build_space()`, package spec guidelines, and system integration guides. |
| `get.cpkg.dev` | **Shell / Binary Installer:** Endpoint for zero-dependency bootstrap scripts (e.g., `curl -sSf https://get.cpkg.dev`). |
