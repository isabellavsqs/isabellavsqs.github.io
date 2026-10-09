# Change 1 — Visual refresh plan

## Goal

Make the portfolio feel more distinctive, colorful, and interactive while keeping it polished and credible for a consultant and MBA candidate. The visual direction should feel confident and warm, not childish.

## Current baseline

The site currently uses a warm paper background, dark green text and links, muted clay accents, a large serif display heading, and a mostly single-column layout. This update should build on that clear, responsive structure rather than replace it.

## Planned changes

- Introduce a restrained but more expressive palette: retain a warm neutral base and add a small number of stronger, coordinated accent colors for headings, labels, links, and selected panels (especially green, blue and orange).
- Create clearer typographic contrast between the hero, page titles, section headings, labels, metrics, and supporting text. Use size, weight, and accent color to guide attention without making the pages busy.
- Add subtle interaction states to navigation, links, impact figures, and relevant content panels. Keep motion brief and restrained, with clear hover, keyboard-focus, and active states.
- Preserve semantic HTML, keyboard access, visible focus indicators, and sufficient text/background contrast. Respect reduced-motion preferences.
- Keep the mobile layout comfortable at 375px and the desktop layout balanced at 1280px. Avoid horizontal scrolling and dense card grids.
- Keep the site static: no JavaScript dependency, animation library, tracking, forms, backend, or database.
- Preserve the existing page content and personal details: describe Isabella as a consultant, mention her Brazilian roots and German-school education, and use LinkedIn as the only contact method.

## Done when

- The overall design is visibly more colorful and engaging, but still professional and restrained.
- Type size and color create a clear hierarchy across all four pages.
- Interactive details work with mouse and keyboard and do not rely on motion.
- The Jekyll build succeeds; all four pages and navigation work; mobile and desktop layouts remain readable; color contrast remains accessible.

## Implementation sequence

1. Review the existing site styles and page structure.
2. Apply the visual changes to the shared styles and only adjust markup where needed to support the hierarchy or interaction.
3. Check Home, About, Work Experience, and Contact at 375px and 1280px.
4. Re-run the Jekyll build, link checks, and Lighthouse checks.

**Status:** Implemented and verified. All four pages were checked at 375px and 1280px; the Jekyll build, doctor, route and internal-link checks, and tested contrast pairs pass. Mobile and desktop Lighthouse scores: 100 Performance, Accessibility, and Best Practices. SEO scored 66 because the Replit preview adds an `X-Robots-Tag: noindex` header; this is not a site-level directive.
