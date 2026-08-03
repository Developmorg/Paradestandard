# Parade Standard — website bundle (editable)

This folder is your website, set up so you can edit the **text, logo and photos** yourself.

## What's in here
- `index.html` — the website
- `images/` — the logo and all photos (logo.png, bed-1..4.jpg, founder.jpg, favicon.png, and a slot for west-cornwall.jpg)
- `cloudcannon.config.yml` — settings for the editor

## To publish AND edit it yourself (CloudCannon)
1. Go to **cloudcannon.com** and sign up (free to start).
2. Create a new site. When it asks for the source, **upload this whole folder** (or connect it from a GitHub repo / Dropbox if you prefer).
3. CloudCannon reads `index.html` and finds the editable bits automatically:
   - **Text** — anything marked editable (headline, service descriptions, story, FAQ, contact). In the Visual Editor you click the text on the page and type over it.
   - **Images & logo** — click any image on the page to upload a new one. To change the logo, replace **images/logo.png**.
4. Open the **Visual Editor**, make your changes, and hit **Save**.
5. To use your domain: **Site Settings → Domains → add paradestandard.com**, then paste the DNS records it gives you at your domain registrar.
6. **Publish**.

## Just want it LIVE quickly (no editing setup)?
Drag this whole folder onto **Cloudflare Pages** or **Netlify** (both free) and it goes live exactly as-is, images and all. To make changes later you'd re-upload — or send them to me.

## Notes
- To swap the "West Cornwall" photo, add an image named **west-cornwall.jpg** into the images folder.
- The animated seascape, slideshow and moving sun are built-in effects — they stay as they are (nothing to edit there).
- Keep image files reasonably sized (under ~1MB each) so the site stays fast.
