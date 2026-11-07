# ruzickaond.github.io

Personal website of Ondřej Růžička, Android developer — live at https://ruzickaond.github.io/

Static, hand-written HTML + CSS, no build step, served by GitHub Pages from `main`.

## Structure

- `index.html` — English (default). Redirects Czech browsers to `/cs/` unless the visitor picked a language (stored in `localStorage` as `ruzickaond-lang`).
- `cs/index.html` — Czech version.
- `style.css` — shared styles (dark theme, same palette as the Luxel site).
- `img/` — app icons and screenshots (ClockOut, Luxel, AllergyTrack).
- `favicon.svg`, `robots.txt`, `sitemap.xml`.

## app-ads.txt — keep it!

`app-ads.txt` must stay at the domain root (`https://ruzickaond.github.io/app-ads.txt`), where AdMob looks for it
for every app whose Play listing website is on `ruzickaond.github.io` (Luxel: `/luxel-web/`, ClockOut: `/clockout-app-web/`).

Publisher ID comes from AdMob → Apps → View all apps → app-ads.txt.
One line per ad network; all apps of the same AdMob account share the line.

## Editing content

Both language files carry the same sections; when changing text, update `index.html` and `cs/index.html` together.
