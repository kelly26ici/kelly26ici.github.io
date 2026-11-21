# Rex Kelly — Personal Portfolio

The source for [kelly26ici.github.io](https://kelly26ici.github.io/), a responsive, static portfolio site for Rex Kelly, AI Engineer.

## Contents

- `index.html` — complete website markup, styles, and lightweight interactions.
- `robots.txt` — allows public crawling and points crawlers to the sitemap.
- `sitemap.xml` — lists the canonical portfolio homepage.
- No build step, package manager, JavaScript framework, or third-party runtime dependency is required.

## Run locally

From the repository root:

```sh
python -m http.server 8000
```

Open http://localhost:8000.

## Publish with GitHub Pages

In the repository settings:

1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and the **/ (root)** folder, then save.
4. GitHub Pages will publish the site at https://kelly26ici.github.io/.

If Pages is already configured for this repository, merging changes into `main` should trigger a deployment automatically.

## Updating the site

Edit `index.html`, preview it locally, and submit changes through a feature branch and pull request. Keep the Google Search Console verification meta tag in the document head unless the site is re-verified with a replacement token.
