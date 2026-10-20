# Fan Travel Service — static website

Plain static HTML/CSS/JS; no build step.

## Deploy to Hostinger

1. hPanel → Websites → your domain → **File Manager** (or **Git** under Advanced).
2. Upload the contents of this repo into `public_html/` (keep `.htaccess`), or connect this GitHub repo with the Git tool, branch `main`, install path `public_html`.
3. Visit the domain — `/` serves `home.html`, and clean URLs like `/about-us` work via `.htaccess`.
