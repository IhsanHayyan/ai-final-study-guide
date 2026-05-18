# GitHub Pages Release Notes

Use `index.html` as the static page entry point.

## Quick Publish

1. Create a GitHub repository.
2. Upload `index.html` to the repository root.
3. Go to repository **Settings > Pages**.
4. Set **Build and deployment** to deploy from the main branch root.
5. Open the GitHub Pages URL after deployment.

## Notes

- The page is static HTML, CSS, and JavaScript.
- The layout is styled like a dark final-exam study guide: fixed chapter-only sidebar navigation, one active chapter page at a time, cards, badges, and reveal/copy buttons for diagrams.
- The home page lists all 11 chapters from first to last.
- Exam subtopics are highlighted inside their chapter pages with a red panel and `EXAM TOPIC` badge.
- Diagrams are written as Mermaid diagrams inside the HTML.
- Mermaid rendering loads from the public CDN `https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs`.
- If you need the page to work fully offline, Mermaid would need to be bundled locally.
