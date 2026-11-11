# Chinese Stamp Generator

A single static page (`index.html`) that turns a Chinese character into a 3D-printable square stamp (STL). No build step, no server code — everything runs in the browser.

Defaults: 26 × 26 × 10 mm, character raised 5 mm, mirrored, centred.

## Run locally

```bash
python3 -m http.server 5178
```

Then open http://localhost:5178

## Deploy for free

Any static host works, because the app is just this folder:

- **Netlify Drop** — drag this folder onto https://app.netlify.com/drop
- **Cloudflare Pages** — create a Pages project, "Upload assets", choose this folder
- **GitHub Pages** — push this folder to a repo, then Settings → Pages → deploy from branch

## Fonts

The default style is 英椎楷書 (Eizui Kaisho) by AC Works, loaded from `fonts/ackaisyo.ttf`. The other built-in styles are SIL Open Font License fonts loaded from the Google Fonts repository via jsDelivr. "Upload font…" uses any `.ttf` / `.otf` from your computer without uploading it anywhere.
