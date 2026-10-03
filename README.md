# Statum GitHub Pages site

A lightweight, dependency-free landing page for Statum Company Ltd., designed to be deployed as a GitHub Pages site or to a custom domain.

## What the page communicates

- Statum is a Nairobi-based software engineering company founded in 2017.
- The company builds custom business systems, web and mobile products, APIs and system integrations, practical AI features, and cloud/support solutions.
- The delivery approach is **Understand - Build - Improve**.
- Public examples include M-Pesa payment integrations, the Kenya PAYE calculation engine, and business management/workflow systems.
- The page sends project enquiries to `info@statum.co.ke`, support enquiries to `support@statum.co.ke`, and links back to Statum's official website and social profiles.

## SEO and accessibility included

- Semantic landmarks, one descriptive `<h1>`, keyboard-visible focus states, a skip link, labelled navigation, reduced-motion support, and an accessible mobile menu.
- Page title, description, canonical URL, Open Graph/Twitter metadata, theme color, favicon, robots policy, sitemap, and JSON-LD for the organisation/service.
- No framework or runtime dependency, so the page is fast to serve from GitHub Pages.
- The header/footer logo and favicon are the local copies of Statum's official assets from `https://statum.co.ke/`.
- `assets/statum-logo.png` is a local raster copy used when a social card needs a PNG logo.
- The social sharing card is available as `og-image.png` for broader Open Graph and Twitter compatibility; `og-image.svg` remains the editable source.

## Deploy

1. Create or open the GitHub repository that will host the page.
2. Commit the files in this directory to the publishing branch.
3. In GitHub, open **Settings - Pages**, choose **Deploy from a branch**, and select the publishing branch and `/ (root)` folder.
4. If using a project URL rather than `https://statum.co.ke/`, update the canonical URL, `og:url`, social image URLs, and the sitemap host in `index.html`, `robots.txt`, and `sitemap.xml`.
5. If connecting `statum.co.ke`, configure the DNS records in GitHub Pages and add a `CNAME` file only after the intended Pages domain is confirmed.

## Content basis

The copy is based on the public Statum website, services, portfolio and company pages, plus the linked public social profiles. It intentionally avoids publishing confidential client names or unsupported performance claims.
