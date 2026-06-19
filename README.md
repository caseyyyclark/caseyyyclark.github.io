# Casey Clark — personal academic website

A single-file static site (no Jekyll build needed — GitHub Pages serves `index.html` as-is).

## Deploy (matches your tutorial's steps)

1. **Buy the domain** on Cloudflare Registrar. If you pick something other than
   `caseyhclark.com`, find-and-replace it across `index.html`, `robots.txt`,
   `sitemap.xml`, and `CNAME` (it appears in the canonical URL, Open Graph tags,
   JSON-LD, and the sitemap).
2. **Create the GitHub Pages repo** and copy ALL of these files into the repo root.
3. **Point the domain at GitHub Pages** in Cloudflare DNS. The `CNAME` file tells
   GitHub which custom domain to serve.
4. **Submit to Google Search Console** and submit `sitemap.xml`.

## Fill in before/after launch (search the file for these)

- [ ] Replace `assets/headshot.jpg` with a real square photo (~600×600) if you want
      a photo for the social card. The current file is a vortex placeholder.
- [ ] Your phone number is on the public CV (assets/cv.pdf). Remove it if you'd
      rather it not be public.
- [x] Profile links wired in: Google Scholar, ORCiD, LinkedIn (GitHub omitted).
- [ ] THIRD RESEARCH INTEREST is a placeholder ("Symmetry-engineered magnetism in
      2D", the altermagnetism side project). Swap it once your third PhD direction
      is settled — see the HTML comment above that block.

## Notes on this revision

- The hero figure is a still rendered directly from your three.js model — the Berry
  connection as a tangent vector field on the BZ torus, winding once around the
  vortex core (C = 1). It is embedded directly in `index.html` as a data URI, so it
  always displays even if the file is opened on its own. A standalone copy of the
  image is also kept at `assets/hero-vortex.png`.
- The figure is static (no interactive link).

## SEO already built in

- Person JSON-LD structured data, canonical URL, Open Graph + Twitter cards with a
  custom social image, robots.txt + sitemap.xml, semantic HTML, mobile responsive.
