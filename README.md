# Sureways Trucking Company Website

Static multi-page website built for GitHub + Cloudflare Pages.

## Files
- `index.html` — Homepage
- `about.html` — About page
- `services.html` — Services page
- `safety.html` — Safety & Compliance page
- `contact.html` — Contact page
- `styles.css` — Shared styling
- `assets/` — SVG visuals and favicon

## Deploy to GitHub + Cloudflare Pages
1. Create a GitHub repository.
2. Upload all files in this folder to the repo root.
3. In Cloudflare Pages, choose **Connect to Git**.
4. Select the repository.
5. Framework preset: **None**.
6. Build command: leave blank.
7. Build output directory: `/` (root).
8. Deploy.

## Custom domain
After deployment, add your custom domain in Cloudflare Pages and update DNS according to Cloudflare prompts.

## Form integration
The contact form is currently static. To make it work:
- Formspree
- Basin
- Cloudflare Worker endpoint

## Final edits recommended
- Confirm office address and phone number
- Replace placeholder hours if needed
- Add legal pages if desired (Privacy Policy, Terms)
- Connect quote form to email/CRM
