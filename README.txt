FLOOR PLATE RAW MATERIAL OPTIMIZER — PRIVATE WEB APP PACKAGE

Contents
- index.html : the application
- manifest.webmanifest : allows installation as a phone/desktop web app
- sw.js : basic offline caching after first load

Recommended deployment
1. Put these files in a private Git repository or upload them to a static web host.
2. For a private team deployment, Cloudflare Pages + Cloudflare Access is a good option.
3. Configure Access to allow only your team's email addresses.
4. Open the resulting web address on Windows/Chrome/Edge and iPhone/Safari.

Important
- Excel upload currently uses SheetJS from its CDN, so the first Excel-import operation needs internet access.
- The optimizer itself runs in the browser.
- No project JSON/database is required.
- Use PRINT / SAVE PDF to keep each optimization result.
