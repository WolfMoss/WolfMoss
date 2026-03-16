# AGENTS.md

## Cursor Cloud specific instructions

This repository is a **GitHub Profile README** — a static Markdown + SVG portfolio page rendered by GitHub on the user's profile. It contains only two files: `README.md` and `snake.svg`. There is no application code, no build system, no dependency manifests, and no automated tests.

### Developing

- **Lint**: `markdownlint README.md` (installed globally via `npm install -g markdownlint-cli`). Pre-existing style warnings (line-length, table column style, inline HTML) are expected and should not be "fixed" without the user's request.
- **Preview**: `grip README.md <port>` renders the README using GitHub-flavoured Markdown styling. Requires `pip install grip`. Example: `grip README.md 6419` then open `http://localhost:6419/`.
- **SVG**: `snake.svg` is a self-contained animated SVG; open it directly in a browser to verify.

### Notes

- No services, databases, or infrastructure are required.
- The README is written in Chinese (中文).
