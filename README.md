# Keun-Young Yook — personal website

A self-contained academic website built with HTML, CSS, and a small progressive-enhancement script. No framework, external fonts, analytics, or third-party scripts are required.

## Files

- `dist/index.html`: profile, appointments, publications, education, presentations, and skills
- `dist/assets/style.css`: desktop, mobile, and print layouts
- `dist/assets/site.js`: active navigation indicator; content and links work without JavaScript
- `dist/assets/Keun_Young_Yook_CV.pdf`: downloadable two-page CV

Open `dist/index.html` directly, or serve `dist` with any static HTTP server. Upload the contents of `dist` to any static hosting provider.

## Publishing

This site uses the GitHub repository `keunbbang/keunbbang.github.io`. The source branch is `codex/site`. GitHub Pages serves the root of the `codex/pages` branch, which contains only the contents of `dist`.

After editing and committing on `codex/site`:

```sh
git push origin codex/site
git subtree push --prefix dist origin codex/pages
```

## Content updates

Content reflects the CV updated in September 2026. Review present appointments, manuscript statuses, publication citations, the CV PDF, and the footer date when updating. Author positions are marked as co-author or first author according to the CV. Manuscripts are clearly separated from published articles. The site contains no detailed research descriptions.
