# Sun Guozheng — Personal Website

An English-language personal homepage for research, engineering, and selected work.

## Structure

- `index.html` — homepage content, metadata, and sections
- `assets/site.css` — responsive visual design
- `assets/site.js` — scroll reveals, mobile navigation, and copyright year
- `assets/favicon.svg` — custom site icon
- `about/index.html` — redirect from the former About URL
- `_layouts/`, `_includes/`, and `_sass/` — retained legacy Jekyll theme files

## Hosting

The site is intentionally buildless, using plain HTML, CSS, and a small amount of JavaScript.
It can be served directly or published through GitHub Pages. Legacy theme files are
retained for compatibility with the existing repository. The default Jekyll sample post
was removed from the published site.

The `CNAME` file retains the existing custom domain. Change it only when the new
domain is ready and DNS has been configured.

## Local preview

From the repository root:

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000` to inspect the site.

## Updating content

All public biography and project descriptions are in `index.html`. The page deliberately
avoids non-public performance metrics and does not list unpublished manuscripts as publications.
