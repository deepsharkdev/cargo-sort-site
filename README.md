# cargosort.ishbul.org — Cargo Sort pages

Published with GitHub Pages from
[deepsharkdev/cargo-sort-site](https://github.com/deepsharkdev/cargo-sort-site).
This folder is the source; copy it into that repository to update the site.

| File                 | Public URL                              | Used by                                   |
| -------------------- | --------------------------------------- | ----------------------------------------- |
| `index.html`         | `https://cargosort.ishbul.org/`         | Support URL in App Store / Google Play    |
| `privacy/index.html` | `https://cargosort.ishbul.org/privacy/` | Game settings, AdMob GDPR message, stores |
| `terms/index.html`   | `https://cargosort.ishbul.org/terms/`   | Game settings                             |
| `app-ads.txt`        | `https://ishbul.org/app-ads.txt`        | AdMob                                     |

`app-ads.txt` must also be uploaded to the root of the main site `ishbul.org`
(the developer website in the stores): AdMob reads it from the domain root,
not from this subdomain.

DNS (Namecheap): `CNAME cargosort → deepsharkdev.github.io`.

The game's links live in `apps/game/src/config.ts` (`LEGAL_URLS`).
