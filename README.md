# ExCos3D - Link Hub

A secure, static, self-hosted central hub linking all ExCos3D Platforms & Socials.

## Overview

A minimalist, privacy-focused link hub built with pure HTML + CSS.  
No trackers, no frameworks, no analytics — fully self-contained and hosted via GitHub Pages.

## Live Site

➡ **[ExCos3D Link Hub](https://excos3d.github.io/)**

## Structure

- `index.html` — main hub page
- `pgp.html` — authenticity, cryptographic identity, and public PGP key
- `license.html` — license, copyright, and data privacy notice
- `/assets/`
  - `/img/` — backgrounds, headers, and branding images
  - `/icons/` — favicons and manifest icons
  - `/fonts/` — locally hosted **Exo 2** webfont (SIL OFL 1.1)
  <!-- - `/signatures/` — detached PGP signature files (optional integrity verification) -->
<!-- - `/scripts/` — lokal .js files for modular features -->
- `/styles/` — CSS files (layout, design, responsiveness)
- `site.webmanifest` — PWA metadata and app manifest
- `sitemap.xml` — search index of all site pages
- `robots.txt` — crawler & indexing rules
- `README.md` — project overview and file integrity notes (this file)

<!--
Each repository file has a corresponding `.sig` file for verifying authenticity and integrity.

- `index.html.sig`
- `pgp.html.sig`
- `license.html.sig`
- `linkhub_style.css.sig`
- `/src` —  Each asset is accompanied by its respective `.sig` file to ensure file integrity.
- `site.webmanifest.sig`
- `sitemap.xml.sig`
- `robots.txt.sig`
- `README.md.sig`-->

## Security & Privacy

- Content Security Policy (CSP) hardened for full self-containment  
- HTTPS enforced (GitHub Pages with Let’s Encrypt TLS)  
- No external scripts, analytics, or cookie usage  
- Self-hosted font and local assets only
  
## License

All ExCos3D content © 2025 ExCos3D — All rights reserved.  
The **Exo 2** typeface © 2013 The Exo 2 Project Authors ([Natanael Gama](https://github.com/googlefonts/Exo-2.0)), licensed under the [SIL Open Font License 1.1](https://openfontlicense.org).
