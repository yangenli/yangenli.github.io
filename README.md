# Yangen Li — Personal Homepage

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fyangenli.github.io&label=yangenli.github.io&up_message=online&style=flat-square)](https://yangenli.github.io)
[![Built with HTML & CSS](https://img.shields.io/badge/built%20with-HTML%20%26%20CSS-16181d?style=flat-square)](#)

Source for my personal academic homepage, live at **<https://yangenli.github.io>**.

I'm a Ph.D. candidate in Finance at the University of Iowa, building machine-learning
and large-language-model methods for financial markets.

## Tech

- **Single page** — plain HTML & CSS with all styles inline in `index.html`; no build step, no dependencies.
- **Typeface** — [Inter](https://rsms.me/inter/).
- **Hosting** — GitHub Pages (branch `main`, path `/`).

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The entire website |
| `Yangen_Li_CV.pdf` | Curriculum vitae, linked from the page |
| `README.md` | This file |

## Local preview

Open `index.html` in any browser, or serve the folder:

```bash
python -m http.server 8000   # then visit http://localhost:8000
```

## Deploy

```bash
git add .
git commit -m "Describe the change"
git push
```

GitHub Pages rebuilds automatically (about 1–2 minutes).

## License

© Yangen Li. All rights reserved. You're welcome to take inspiration from the layout.
