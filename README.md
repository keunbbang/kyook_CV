# Kyook CV — Keun-Young Yook

A self-contained academic website built with HTML, CSS, and a small progressive-enhancement script. No framework, external fonts, analytics, or third-party scripts are required.

## Files

- `dist/index.html`: profile, appointments, publications, education, fellowship, presentations, and skills
- `dist/assets/keun-young-yook.jpg`: original portrait from the CV
- `dist/assets/style.css`: desktop, mobile, and print layouts
- `dist/assets/site.js`: active navigation indicator; content and links work without JavaScript
- `dist/assets/Keun_Young_Yook_CV.pdf`: downloadable two-page CV

Open `dist/index.html` directly, or serve `dist` with any static HTTP server. Upload the contents of `dist` to any static hosting provider.

## Publishing

Repository: [keunbbang/kyook_CV](https://github.com/keunbbang/kyook_CV)

Website: [Kyook CV](https://keunbbang.github.io/kyook_CV/)

The source branch is `codex/site`. GitHub Pages serves the root of the `codex/pages` branch, which contains only the contents of `dist`. Asset links are relative, so the site works under the `/kyook_CV/` project path without a build step.

After editing and committing on `codex/site`:

```sh
git push origin codex/site
git subtree push --prefix dist origin codex/pages
```

## Content updates

Content reflects the CV updated in September 2026. Review present appointments, manuscript statuses, publication citations, the CV PDF, and the footer date when updating. Author positions are marked as co-author or first author according to the CV. Manuscripts are clearly separated from published articles. The site contains no detailed research descriptions.


## License

Website code is available under the [MIT License](LICENSE). The license covers the HTML structure, CSS, JavaScript, and code-based favicon. The portrait, CV PDF, personal profile content, and third-party publication content are excluded; see [NOTICE.md](NOTICE.md).

To reuse the template, replace the name, portrait, CV, contact details, publications, and canonical/social metadata with your own information.
