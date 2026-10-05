# Isabella Vasques Portfolio

A static Jekyll site for the GitHub Pages user site `isabellavsqs.github.io`. The website source is at the repository root; it does not require a Node app, backend, database, or manual build step for GitHub Pages.

## Pages and content

- `index.md` — Home
- `about.md` — About
- `work-experience.md` — Work Experience
- `contact.md` — Contact (LinkedIn only)
- `_layouts/default.html` and `_includes/` — shared page structure and SEO metadata
- `assets/css/site.css` — responsive styling
- `_config.yml` — site URL, empty `baseurl`, and build exclusions

Edit page text in the Markdown files. Keep personal source documents out of the public repository; `attached_assets/` is excluded from Git and the built site.

## Preview locally

Install Ruby 3.x and Jekyll once, then run from the repository root:

```sh
gem install jekyll
jekyll serve
```

Open `http://127.0.0.1:4000`. To create a local build in `_site/`, run:

```sh
jekyll build
```

`_site/` is generated output and is not committed.

## Publish with GitHub Pages

1. Create or use the GitHub repository named `isabellavsqs.github.io`.
2. Push the complete project root to its `main` branch.
3. In the repository’s **Settings → Pages**, choose **Deploy from a branch**, select `main`, and select `/(root)`.
4. Save. GitHub Pages builds the Jekyll site directly; no separate build workflow is needed.

The configured canonical URL is `https://isabellavsqs.github.io/`, and `_config.yml` intentionally leaves `baseurl` empty.

## Lighthouse

Preview the site locally or wait until GitHub Pages is live, then run Lighthouse in Chrome DevTools for the mobile and desktop views. Check Performance, Accessibility, Best Practices, and SEO; the target for each is 90 or higher. The site uses local assets, semantic HTML, descriptive metadata, keyboard focus styles, and no third-party trackers.
