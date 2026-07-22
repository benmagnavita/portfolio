# Ben Magnavita — Security Portfolio

Terminal-themed portfolio site. Pure HTML/CSS — no build tools, no dependencies.

## Structure

```
portfolio/
├── index.html        # Splash page (resume)
├── projects.html     # Projects grid
├── siem-lab.html     # Home SIEM Lab walkthrough
└── assets/
    ├── style.css     # Shared stylesheet (all theming lives here)
    └── img/          # Screenshots and thumbnails
```

## Preview locally

Open `index.html` in any browser. That's it.

## Host for free (GitHub Pages)

1. Create a new public repo (e.g. `ben-magnavita.github.io` for a root URL,
   or any repo name for `username.github.io/repo-name`).
2. Push these files to the repo root.
3. Repo Settings → Pages → Source: `main` branch, `/ (root)` → Save.
4. Site is live in ~1 minute.

Other free options: Netlify or Cloudflare Pages (drag-and-drop the folder).

## Add a new project

1. **Copy `siem-lab.html`** → rename it (e.g. `phishing-lab.html`).
2. Update the title, README terminal block, and replace the step sections
   with your own. Each step is a self-contained `<div class="step">` block —
   duplicate or delete as needed.
3. Drop your screenshots into `assets/img/` (numbered names keep them tidy).
4. **Open `projects.html`** and copy the existing project card block —
   instructions are in an HTML comment right where you need them.
   Point the card's `href` at your new page and pick a thumbnail.

## Tweak the theme

All colors are CSS variables at the top of `assets/style.css`.
Change `--green` to re-accent the whole site in one line.
