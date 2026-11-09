# EHL B2B — Netlify deployment package

Target project: ehl-b2b (https://ehl-b2b.netlify.app).

This package contains 13 named site pages: four existing full pages and nine approved minimal template pages. Every page keeps its exact registered filename and all validated filename links.

`index.html` is an exact copy of `EHL_B2B_Homepage.html` so the site root works on static hosting. It is a technical entry alias, not a fourteenth business page. The logo and menu still use the named HTML files.

Upload the contents of this folder as one Netlify deploy. Keep all HTML files at the same level. No build, dependencies or environment variables are needed. `netlify.toml` declares a static publish directory and disables Pretty URLs for filename navigation when the host reads that configuration. Existing per-page compatibility scripts are preserved.

The site is a public review prototype. `_headers` asks search engines not to index it. There is no password added by this package.

The nine template pages contain only their shared header, breadcrumb, title, white space and footer. Forms on the existing pages remain demonstrations without sending or storage. Team videos remain placeholders.

Validation covers local file targets, section anchors, page counts and source integrity. Deployment still requires a successful upload; this README is not a deployment receipt.
