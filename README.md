# qunzhixu.github.io

Personal academic homepage of Qunzhi Xu, served by GitHub Pages at https://qunzhixu.github.io/.

Plain static site, no build step:

- `index.html` — all content (about, research, publications, awards, teaching, service)
- `assets/css/style.css` — styling, including dark mode and the mobile layout
- `assets/img/profile.jpg` — portrait; `assets/files/curriculum_vitae.pdf` — CV
- `.nojekyll` — tells GitHub Pages to serve the files as they are

Preview locally:

```bash
python3 -m http.server 8765
```

then open http://127.0.0.1:8765/. Pushing to `main` publishes the site within about a minute.
