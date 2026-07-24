# trowser.github.io

Public site for **[Trowser](https://trowser.github.io/)** — Exploratory Tester’s Companion.

Static HTML/CSS only (no build step). GitHub Pages serves from `main`.

## Local preview

Open `index.html` in a browser, or from this folder:

```bash
npx --yes serve .
```

## Update docs from the main Trowser repo

Copy newer versions when the app docs change:

- `src/Trowser/Resources/manual.html` → `docs/manual.html` (keep site header; icon → `../assets/trowser.png`)
- `src/Trowser/Resources/script-help.html` → `docs/script-help.html` (wrap body content in `.doc-body`; keep site header)
- `trowserkit/trowser-api-index.md` → `docs/trowser-api-index.md` (regenerate `docs/api.html` with a simple Markdown-to-HTML pass)

## Links

- Download: https://www.thetesteye.com/code/Trowser.zip
- Manual PDF: https://www.thetesteye.com/papers/TamingTheTrowser.pdf
- Demo: https://youtube.com/watch?v=mQnYhafyqks
- Issues: https://github.com/Trowser/Trowser/issues
