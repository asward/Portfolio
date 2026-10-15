# Portfolio

Personal portfolio site for Andrew Ward. Plain static HTML and one stylesheet; no build step.

- `index.html` – home
- `projects/index.html` – project cards; `projects/<name>/` – one folder per project (page + images)
- `resume.html` / `Resume.pdf` – resume
- `skills.html` – full skills list
- `about.html` – about page; photos in `img/about/`

## Publish

Settings → Pages → Deploy from branch → `main`, `/ (root)`. For a custom domain, set it there and add the DNS records GitHub lists.

## Photos

Each project folder holds its `index.html` and images. Replace `cover.svg` with a real photo (e.g. `cover.jpg`, ~200–400 KB) and update the two references: the `<img>` in that project's `index.html` and its card in `projects/index.html`.
