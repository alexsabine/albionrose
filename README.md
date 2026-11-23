# Albion Rose

The holding page for **albionrose.ai**: a pedagogical platform in preparation, by Alexander Sabine.

**Live site:** https://albionrose.ai/ (GitHub Pages, served from `main`)

It is one self-contained page with no build step.

## What is here

| Path | Purpose |
| --- | --- |
| `index.html` | The whole site: markup, styles, the sphere at the top, the three small pictures of the method, and the in-page viewer. |
| `films/` | The introduction film and the poster frames for the films shown on the page. |
| `img/` | Pictures for the six example tiles, the sphere (`ball.png`, and the 1024-pixel master), and the larger icons. |
| `favicon.ico`, `favicon-32.png`, `apple-touch-icon.png`, `site.webmanifest` | Site icons, all made from the sphere. |
| `robots.txt`, `sitemap.xml` | For search engines. |
| `CNAME`, `.nojekyll` | GitHub Pages settings. Do not remove. |
| `LICENSE`, `MARK.md` | Ownership, and a note on the sphere as a mark. |

## How it relates to the other sites

- The six example simulations and two of the films are hosted in the Museum at https://www.temporalgrammar.ai/. On this page they open in a frame, so a visitor stays on Albion Rose. Links that do leave the site open in a new tab.
- https://www.honami.co.uk/ is the author's professional profile.

## Changing it

Edit `index.html`, commit, and push to `main`. The page updates within a few minutes.

Search engines read the block of structured data near the end of the `<head>` (who the author is, the films and their transcripts). If a film or its wording changes, update that block and the transcript under the film together.
