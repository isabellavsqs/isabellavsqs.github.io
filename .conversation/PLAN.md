# Portfolio Site Plan

## Goal
Create a publish-ready Jekyll GitHub user site for `isabellavsqs.github.io`. Keep the complete site at the project root, set `baseurl` to an empty string, and use URL filters for internal links.

## Pages and design
- Home, About, Work Experience, and Contact pages, with shared navigation and footer.
- Light-only, responsive single-column layout with accessible contrast and semantic HTML.
- Warm, approachable typography and clear, concise section hierarchy, using the supplied reference as inspiration without copying its brand or assets.

## Content
- Use only biography and work details supplied in the résumé/documents; do not fetch personal details from the LinkedIn URL or invent achievements.
- Mark missing biography and experience details as placeholders.
- The user is comfortable with a public `mailto:` link, but has not supplied an address; leave it as a placeholder until provided.

## Implementation and checks
- Markdown pages with YAML front matter; reusable Jekyll layouts and includes.
- Plain HTML and CSS with minimal JavaScript; no backend, database, framework, form backend, animation system, or third-party trackers.
- Include SEO metadata, a sitemap, a favicon, and a README covering updates, local preview, and Lighthouse.
- Keep `index.md`, `_config.yml`, `_layouts`, `_includes`, assets, and all other site files directly in the project root.
- Check navigation and layouts at 375px and 1280px, run the available Jekyll/GitHub Pages build check, and target Lighthouse scores of at least 90 in Performance, Accessibility, Best Practices, and SEO.

## Assumptions
- The target GitHub Pages URL is `https://isabellavsqs.github.io/`; the GitHub repository and its Pages settings have not been provided, so this plan covers a correctly structured, publish-ready site rather than publishing it.
- Content placeholders remain until the résumé/documents and public email address are supplied.
