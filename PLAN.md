# Isabella Vasques Portfolio — Plan

## Goal and structure
Build a static Jekyll GitHub user site for `isabellavsqs.github.io`, with `baseurl` empty and URL filters for links. The complete site will live directly in the project root and publish from GitHub Pages’ `main` branch and `/` root.

## Pages and content
- **Home:** concise introduction presenting Isabella as an IESE MBA candidate and former BCG consultant working across strategy and social impact.
- **About:** draw on the supplied documents for her Brazilian/German background, values of generosity and continuous learning, volunteer work, and interests. Leave out intimate family details.
- **Work Experience:** use the CV as the source of dates, titles, education, and impact figures for BCG, IFC, SMU Investimentos, Mercedes-Benz, and Somos Educação. Include selected examples such as the €80M value-lever model, 200+ FTE organization redesign, €5M project-cost offset, €20M annual margin opportunity, 40% reduction from a €500M bid, and €77M social-impact-linked loan.
- **Contact:** link to LinkedIn and use the CV email (`isabella.vasques@iese.net`) as the public `mailto:` address, consistent with the user’s consent. Do not publish the phone number.
- Use LinkedIn’s public indexed profile details to confirm her IESE MBA candidacy and specialties (energy, infrastructure, financial services, growth and innovation, turnarounds, organization redesign, and pricing). The CV remains authoritative for career history and dates.

## Design and implementation
- Light-only, responsive single-column presentation with warm, approachable typography, accessible contrast, semantic HTML, and shared navigation/footer.
- Markdown pages with YAML front matter; reusable Jekyll layouts/includes; plain HTML and CSS with minimal JavaScript.
- Include SEO metadata, sitemap, favicon, and README instructions for editing, local preview, and Lighthouse. No backend, database, contact form, app framework, or third-party trackers.
- Use the supplied reference for its clear messaging and human-centered presentation, without copying its identity or assets.

## Root-only cleanup and verification
- Replace the generated API, design-preview, and pnpm workspace scaffolding with the Jekyll site so the project does not contain a separate application or monorepo.
- Confirm the required Jekyll files and assets are at the root; check the GitHub Pages-compatible build, page links, and 375px/1280px layouts; target Lighthouse scores of 90+ in all four requested categories.

## Assumptions
- There is no supplied headshot or portfolio project list, so the design will not invent either.
- Publishing to GitHub is not included; the source will be structured for `https://isabellavsqs.github.io/`, with setup steps in the README.
