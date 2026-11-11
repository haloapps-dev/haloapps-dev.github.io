# haloapps-dev.github.io

Public website for Halo Apps, served by GitHub Pages at
https://haloapps-dev.github.io. Plain HTML and CSS, no build step.

| Path | What |
| --- | --- |
| `/` | Halo Apps home page |
| `/tidify/` | Tidify app page |
| `/tidify/privacy/` | Tidify privacy policy |
| `/tidify/terms/` | Tidify terms of use |
| `/halo-scan/` | Halo Scan app page |
| `/halo-scan/privacy/` | Halo Scan privacy policy |
| `/halo-reader/` | Halo Reader app page |
| `/halo-reader/privacy/` | Halo Reader privacy policy (Google OAuth consent screen and store listings link here) |
| `/tenniscoach/` | Courtella (serve practice) app page; `courtella.css` adds its boxes on top of `style.css` |
| `/tenniscoach/serve-speed/`, `/tenniscoach/guides/` | Courtella serve guides (one search per page, sources listed, app box after the short answer and at the end) |
| `/territory/privacy.html` | Territory privacy policy (linked from the app, so keep this path) |
| `/tailtick/privacy.html` | Tailtick privacy policy (linked from the app, so keep this path) |
| `/app-ads.txt` | AdMob authorised sellers file |
| `/robots.txt`, `/sitemap.xml` | Crawler rules (OAI-SearchBot and Bingbot welcome, `/go/` excluded) and page list |
| `/<key>.txt` | IndexNow key file; ping https://api.indexnow.org/indexnow after page changes |

To add an app, copy the `tidify/` folder, edit the text, and link it from
`index.html`. Keep `app-ads.txt` at the root.

When you add a page, add it to `sitemap.xml` too.
