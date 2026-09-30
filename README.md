# ossian.games redirect

Sends every visitor of ossian.games (and www.ossian.games) to the same path on
https://ossiandackfors.com, over HTTPS. The real site lives in the `ossian.games` repo.

- `index.html` handles `/`. `404.html` is an identical copy that GitHub Pages serves for every
  other path, so `ossian.games/thrall` becomes `ossiandackfors.com/thrall`.
- `CNAME` claims `ossian.games` for this repo. GitHub also redirects `www.ossian.games` here.
- If ossian.games is not renewed, delete this repo. Nothing else depends on it.
