# Victor Portugal — personal website

Source for my personal page, published with GitHub Pages at
https://portugal-vpv.github.io

A single static page: no framework, no build step, no dependencies.

## Structure

```
index.html          # the whole page (HTML + CSS)
assets/
  profile.jpg       # avatar
  fonts/            # Inter, self-hosted (woff2)
```

## Running locally

Open `index.html` in a browser. To serve it over HTTP instead:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploying

Pushing to the default branch publishes the site through GitHub Pages
(Settings → Pages → Deploy from a branch → `/ (root)`).

## Notes

- Fonts are self-hosted, so the page makes no requests to third-party servers.
- Icons are inline SVGs. The brand icons come from
  [Simple Icons](https://simpleicons.org) (CC0) and the location pin from
  Material Icons (Apache 2.0).
- Inter is licensed under the [SIL Open Font License](https://openfontlicense.org).
- The avatar is a temporary placeholder and should be replaced with my own photo.
- The Games and Music nav items are placeholders for future sections.
