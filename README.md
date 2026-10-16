# yeniji.org — Cargo Sort pages

Static files for the developer website. Upload the contents of this folder to
the root of `https://yeniji.org/` as they are.

| File                            | Public URL                               | Used by                                   |
| ------------------------------- | ---------------------------------------- | ----------------------------------------- |
| `app-ads.txt`                   | `https://yeniji.org/app-ads.txt`         | AdMob (must be at the domain root)        |
| `cargo-sort/index.html`         | `https://yeniji.org/cargo-sort/`         | Support URL in App Store / Google Play    |
| `cargo-sort/privacy/index.html` | `https://yeniji.org/cargo-sort/privacy/` | Game settings, AdMob GDPR message, stores |
| `cargo-sort/terms/index.html`   | `https://yeniji.org/cargo-sort/terms/`   | Game settings                             |

The game's links live in `apps/game/src/config.ts` (`LEGAL_URLS`).
