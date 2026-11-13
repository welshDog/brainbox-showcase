# Brain Box showcase

**Live page: https://welshdog.github.io/brainbox-showcase/**

A single static page that introduces **Brain Box**: an autonomous guardian agent that lives on a Raspberry Pi, looks after a
Docker stack, keeps a tamper-evident journal, and asks before it acts.

This repository holds **only the public showcase page**. The Brain itself is developed privately. Nothing here is live data,
and nothing here can reach a running Brain.

## What's in this repo

| File | Purpose |
|---|---|
| `index.html` | The whole page: markup, styles and a few lines of script. No build step. |
| `.nojekyll` | Tells GitHub Pages to serve the file as it is. |
| `CONTRIBUTING.md` | How to suggest a fix or improvement. |
| `SECURITY.md` | How to report a security or privacy problem. |
| `LICENSE` | MIT licence. |
| `CODE_OF_CONDUCT.md` | How we treat each other here. |
| `.github/` | Issue forms and the pull request template. |

## Design principles

- **Calm and readable first.** Display modes for readable text, high contrast and light/dark theme. Reduced motion is respected.
- **Plain language.** Short sentences, no jargon without a reason.
- **Honest.** The page says what the Brain does today, what it does not do yet, and what is still unsolved.
- **Static and private.** No tracking, no cookies, no external scripts, no live data.

## Preview locally

```
python -m http.server 8080 --bind 127.0.0.1
```

Then open <http://127.0.0.1:8080/index.html>. Stop it with `Ctrl+C`.

## Privacy rule (applies to every change)

This page must never contain addresses, hostnames, ports, tokens, webhook URLs, screenshots of a real dashboard, or copied
journal text. Before opening a pull request run:

```
grep -n -i -E "192\.|10\.|:8765|webhook|sk-|0x[0-9a-f]{6}|\.local" index.html
```

It should print nothing.

## Contributing

Small, kind improvements are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) first.

## Licence

[MIT](LICENSE). This covers the showcase page only, not the Brain itself, which is developed privately.
