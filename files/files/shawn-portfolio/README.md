# Shawn Lee — Portfolio

A single-page portfolio site for Shawn Lee Jun An, a Higher Nitec in Accounting student at ITE College Central. Built as a static site so it can be published directly with GitHub Pages.

## Structure

```
├── index.html      Main page
├── style.css        Styles (ledger / statement-of-account visual theme)
├── script.js        Mobile nav + scroll-reveal
└── assets/
    ├── img/          Photos used across the site
    └── docs/          Downloadable PDF testimonials
```

## Publish with GitHub Pages

1. Create a new repository on GitHub and push these files to it.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, pick the `main` branch and `/ (root)` folder, then **Save**.
4. GitHub will give you a URL like `https://your-username.github.io/repo-name/` — the site is live there within a minute or two.

## To edit

- Update text directly in `index.html` — each section is clearly commented (`<!-- ================= EXPERIENCE ================= -->` etc).
- Swap photos by replacing files in `assets/img/` (keep the same filenames, or update the `src` paths in `index.html`).
- Add your real email/LinkedIn in the footer contact section near the bottom of `index.html`.
