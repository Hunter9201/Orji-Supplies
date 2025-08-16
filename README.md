# Orji Supplies – GitHub Pages

This folder contains a ready-to-deploy one-page website.

## Quick Deploy (Project Pages)
1. Create a new repo, e.g. `orji-supplies`.
2. Add these files at the root:
   - `index.html`
   - `images/` (this folder with your photos)
   - `README.md`
   - `.nojekyll` (prevents Jekyll from interfering with assets)
3. Commit & push to the `main` branch.
4. In **Settings → Pages**, set:
   - **Source**: Deploy from a branch
   - **Branch**: `main` / `/ (root)`
5. Open the URL shown (it will look like `https://<your-username>.github.io/orji-supplies/`).

## Quick Deploy (User/Org Pages)
1. Create repo named **`<your-username>.github.io`**.
2. Put these same files at the repo root and push to `main`.
3. Your site will be live at `https://<your-username>.github.io/`.

## Notes
- Images are referenced **relatively** from the `images/` folder; no absolute paths required.
- Filenames are lowercase and hyphenated (no spaces) for reliability on case‑sensitive hosting.
- To change your WhatsApp number, edit `index.html`:
  ```js
  const WHATSAPP_NUMBER = '2567XXXXXXXX';
  ```
