# Zenventora Beta

Single-page responsive website template for **Zenventora**, a product-focused partnership agency for SaaS startups, software product companies, and digital solution providers.

## What is included

- Responsive one-page landing page (`index.html`)
- Mobile-first styling (`styles.css`)
- Mobile menu, enquiry drawer, and placeholder form behavior (`script.js`)
- SEO metadata, canonical URL, Open Graph, Twitter Card, Organization schema, ContactPoint schema, and FAQ schema
- Partner company placeholder cards for logo, company name, category, and description
- Contact form and floating side enquiry form placeholders
- Legal pages: `privacy-policy.html` and `terms-and-conditions.html`
- Relative interlinking for same-folder hosting
- `robots.txt`, `sitemap.xml`, `llms.txt`, `site.webmanifest`
- SVG favicon, Apple touch icon placeholder, and social sharing OG image

## Placeholder areas to replace

1. Logo / brand mark in `index.html` and `assets/favicon.svg`
2. Partner company logos, names, categories, and descriptions in the `#partners` section
3. Phone number `9876543210`
4. Email addresses `support@zenventory.in` and `Sales@zenventory.in`
5. Form `action="#"` attributes with the final working form endpoint
6. Privacy Policy and Terms & Conditions content/details if your legal team provides final wording
7. `assets/og-image.svg` if a branded social image is available

## Local preview

```bash
python3 -m http.server 4173
```

Open `http://localhost:4173` in a browser.
