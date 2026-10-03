# Rush Rock Trivia 2027

> *"I see the works of gifted hands grace this strange and wondrous land...
> I see the hand of man arise with hungry mind and open eyes."*
> -- Rush, 2112 (The Oracle: The Dream)

## About

**Rush Rock Trivia 2027** is a landing page and future home of the ultimate Rush trivia experience for fans of the greatest progressive rock band in history. After 50 years of Solar Federation control, the Elder Race continues the tour.

Visit the live site: [rush2027.fyi](https://rush2027.fyi)

## Tech Stack

- **HTML5** -- Static single-page site
- **CSS3** -- Custom animations, responsive layout, Google Fonts (Cinzel, Outfit)
- **Hosting** -- Cloudflare Workers (static assets)
- **Domain** -- Cloudflare DNS

## Project Structure

```text
rush-rock-trivia-2027/
  index.html        # Main landing page
  rush-2027.jpg     # Hero image (Rush 2027 Starman graphic)
  og-image.jpg      # 1200x630 social share preview (Facebook, X, etc.)
  images/
    Rush2027RedStar.png # Rush 2027 logo (for the app and share preview)
  README.md         # This file
  LICENSE           # MIT License
  .gitignore        # Git ignore rules
  .markdownlint.json # Markdown linting configuration
  .editorconfig     # Editor configuration for consistent formatting
```

## Deployment

This project is deployed as a static asset Worker on Cloudflare:

1. Log in to the [Cloudflare Dashboard](https://dash.cloudflare.com/).
2. Navigate to **Workers & Pages** > **rush-2027**.
3. Click **New deployment**.
4. Upload the project folder.
5. Click **Deploy**.

The site is served at [rush2027.fyi](https://rush2027.fyi) via a custom domain linked to the Worker.

## Development

This is a static HTML project for now -- no build step required. To preview locally, open `index.html` in any browser or use a local server:

```bash
npx serve .
```

## Related Projects

- [rush-rock-trivia](https://github.com/m2web/rush-rock-trivia) -- The original Rush Rock Trivia app (2026)

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

*Home where we belong -- 2027*
