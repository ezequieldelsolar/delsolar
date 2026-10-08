# Financial Literacy Project — Portable Website

## Entry point

The website entry point is `index.html`.

## Build requirements

No build step is required. This ZIP contains the already-built production website.

## Website type

This is a static website. All charts, survey data, translations, navigation, tabs, responsive styles, photos, the school logo, and fonts are included in the package.

## External dependencies

There are no required external APIs, CDNs, databases, or ChatGPT Sites services. The Geist font files are included locally. The remaining typography uses the browser's built-in Georgia fallback exactly as in the current website.

## Deployment

1. Extract the ZIP.
2. Upload the complete contents of the `financial-literacy-project` folder to your web server's document root (for example `public_html`, `www`, or the configured Nginx/Apache web root).
3. Make sure the server serves `index.html` as the default document.
4. Keep the `_next` directory and every image file in their existing locations.

The compiled website uses root-relative asset paths, so deploy it at the root of a domain or subdomain (for example `https://example.com/` or `https://finance.example.com/`), not inside a nested URL folder.

Optional: after deployment, replace the relative `/og.png` social-image URL in `index.html` with its full public HTTPS URL if you want optimal link previews on social platforms.
