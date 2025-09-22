# IvorySync Landing

A minimal static landing page for IvorySync with a logo and email link.

## Deploy on Vercel
- Create a new project in Vercel and import this folder (or connect a Git repo).
- No build command is needed. Output is at the project root.
- After first deploy, attach `ivorysync.com` and `www.ivorysync.com` to this project in **Settings → Domains**.
- Ensure DNS (at GoDaddy) has:
  - A @ → 76.76.21.21
  - CNAME www → cname.vercel-dns.com

## Customize
- Replace `/assets/ivorysync-logo.svg` with your final logo.
- Update the mailto link in `index.html` if needed.
