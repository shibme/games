# Games

Small, self-contained browser games. The site is static HTML and deploys to GitHub Pages from the `pages/` folder on push to `main`.

**Live site:** [https://games.shib.me](https://games.shib.me)

Point a DNS CNAME for `games.shib.me` at `shibme.github.io`, and keep the custom domain set in the repo’s Pages settings. [`pages/CNAME`](pages/CNAME) is published with the site so GitHub serves that host.

## Games

| Game | Play |
| --- | --- |
| [Tango](pages/tango/) | LinkedIn-style 6×6 sun and moon logic puzzle |

## Add a game

1. Put a self-contained page at `pages/<name>/index.html` (no CDNs; pin any assets in the repo).
2. Add a card to the list in [`pages/index.html`](pages/index.html) with a relative link (`<name>/`).
3. Add a row to the table above.
