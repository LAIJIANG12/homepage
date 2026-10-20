# laijiang12.github.io

Personal homepage of Lai Jiang, published with GitHub Pages at
<https://laijiang12.github.io/>.

A single static page: no build step, no JavaScript, no tracking.

## Structure

| Path | Purpose |
| --- | --- |
| `index.html` | Markup, meta tags, social preview |
| `main.css` | Layout, colors, responsive rules |
| `reset.css` | Meyer's public-domain CSS reset |
| `img/hi.webp` | Animated logo (160×158, ~670 KB) |
| `img/hi-static.webp` | Still frame for `prefers-reduced-motion` users |
| `img/hi.gif` | Fallback for browsers without animated WebP |
| `ds1.webp`, `ds.webp` | Link icon and its hover variant |
| `favicon.png`, `apple-touch-icon.png` | Browser and iOS icons |

## Local preview

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000/>.

## Deploy

Push to `main`; GitHub Pages serves the repository root as-is
(`.nojekyll` turns off the Jekyll build).
