# GitHub Pages Starter (Static)

This is a no‑build static starter you can deploy to GitHub Pages in minutes.

## Quick start

1. Create a new GitHub repo (public is easiest to start).
2. Upload these files (or push via git).
3. Go to **Settings → Pages**:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (root)
4. (Optional) Keep the included GitHub Actions workflow enabled; it will deploy automatically on push.

### Custom domain
- If using a subdomain (e.g. `www.example.com`), add a `CNAME` file at repo root containing `www.example.com` and create a CNAME DNS record pointing to `<username>.github.io`.
- If using the apex (e.g. `example.com`), use your DNS provider's ANAME/ALIAS (or root CNAME flattening) to `<username>.github.io` so you don't have to manage IPs. Then add the same value into **Pages → Custom domain**.

### Local editing
Just edit `index.html` and `styles.css`, commit and push to `main`. The site redeploys automatically.
