# Oceanfront Condominiums Galle — Owner Portal

Static GitHub Pages version of the Oceanfront Condominiums Galle Owner Portal.

## Files

- `index.html` — page structure and content
- `styles.css` — responsive design and styling
- `script.js` — document search and category filters
- `CNAME` — custom domain for GitHub Pages (`ownerportal.oceanfrontcondos.lk`)
- `assets/` — place future logo, photos, PDFs, or other local assets here

## Existing Google Drive collections

The portal currently links to:

1. Owners’ Handbook — `https://drive.google.com/drive/folders/13bYC6awFYJi4uPBYyfdvG92SYqwvI1Cm`
2. Council Meeting Minutes — `https://drive.google.com/drive/folders/1ubzzG08KfHOAfj_shNUpZUlNKOJwMhL_`
3. Constitution & By-laws — `https://drive.google.com/drive/folders/1LX2JXZKn4asyoVvnR0_qtSdcPxfPP_5K`

## Upload to GitHub

1. Create a new GitHub repository.
2. Upload all files and the `assets` folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select `main` and `/ (root)`, then save.
6. Under **Custom domain**, enter `ownerportal.oceanfrontcondos.lk`.
7. Configure the DNS record for the subdomain with your domain/DNS provider as instructed by GitHub Pages.
8. After DNS verifies, enable **Enforce HTTPS**.

## Updating documents

To change a Google Drive destination, edit the relevant `href` in `index.html`.

To add another document collection, duplicate one `.document-card` block in `index.html` and update its category, searchable keywords, text, and link.
