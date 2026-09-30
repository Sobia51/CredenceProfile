# Credence Group LLC — Corporate Profile 2026

Static website. No build step.

## Files
- `index.html` — the full profile. Images, fonts and styles are embedded in this one file.
- `camp-map.html` — the interactive camp map, loaded by `index.html`. Keep it in the same folder.
- `Credence-Group-Profile-2026.pdf` — add this yourself (export from the A4 version). The "Download PDF" buttons link to this exact filename.

## Publish with GitHub Pages
1. Create a new repository and upload all files in this folder to the root.
2. Go to **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main`, folder `/ (root)` → Save.
3. The site goes live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Use your own domain (e.g. profile.credence-group.ae)
1. In **Settings → Pages → Custom domain**, enter `profile.credence-group.ae` and save. GitHub creates a `CNAME` file.
2. At your domain provider, add a DNS record:
   - Type `CNAME`, Name `profile`, Value `<your-username>.github.io`
3. Once DNS updates, tick **Enforce HTTPS**.

## Updating
Replace `index.html` with a new export and commit. Changes go live automatically.
