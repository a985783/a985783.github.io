# Deploy

1. Repo name: `george-onair.github.io` (GitHub user site).
2. Push all files in this folder (including `.nojekyll` and the IndexNow `<key>.txt`) to `main`.
3. Settings → Pages → Source: Deploy from branch `main`, folder `/ (root)`.

## After it's live
1. **Bing Webmaster Tools**: verify via meta tag in `index.html` `<head>` or upload `BingSiteAuth.xml` to root; submit `sitemap.xml`.
2. **Google Search Console**: URL-prefix property `https://george-onair.github.io/`; verify via HTML file in root or meta tag; submit `sitemap.xml`.
3. **IndexNow ping**: see `INDEXNOW_KEY.txt` (confirm the key file URL returns 200 first).
