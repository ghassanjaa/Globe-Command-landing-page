# Globe Command: landing page

Static site (plain HTML/CSS, one tiny inline script, no build step, no external requests) for the iOS game Globe Command. It serves as the App Store Support URL and Privacy Policy URL.

## Deploy on GitHub Pages

Settings > Pages > Build and deployment > Deploy from a branch > `main` / `(root)` > Save.

Pages (replace the base with your Pages URL):

- `/` (index.html): landing page
- `/support.html`: Support URL
- `/privacy.html`: Privacy Policy URL
- `/404.html`: not found page

## Assets to add

- `assets/shots/01-main-menu.png`, `02-battle-map.png`, `03-strike-card.png`, `04-ground-assault.png`, `05-city-rescue.png`, `06-after-action.png`, `07-diplomacy.png` (2868x1320 landscape)
- `assets/og.png` (social preview image). For reliable link previews, change the `og:image` / `twitter:image` meta tags in `index.html` to the full https URL once deployed.

Missing screenshots simply show a placeholder panel.
