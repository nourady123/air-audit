# Air Audit Companion PWA

This version works with a Windows laptop and is designed for iPhone Safari.

## Important
A PWA must be served over HTTPS for installation and offline caching. Opening `index.html` directly from a ZIP is useful only for inspection and will not install correctly.

## Easiest Windows deployment: GitHub Pages
1. Create a free GitHub account and a new repository, for example `air-audit`.
2. Upload all files and folders from this package to the repository root.
3. In the repository, open Settings > Pages.
4. Under Build and deployment, select Deploy from a branch, choose `main` and `/ (root)`, then save.
5. Open the Pages address on the iPhone in Safari.
6. Tap Share > Add to Home Screen > Add.

## Alternative deployment
The same files can be uploaded to Cloudflare Pages, Netlify, or any HTTPS web host. No build command is required. Publish the folder containing `index.html`.

## iPhone use
- Data is saved locally in Safari on that iPhone.
- Use Download backup regularly, especially before clearing Safari website data or changing phones.
- Use Restore backup to recover the JSON backup.
- Use Export complete audit record to share a readable text report.
- Use the normal Camera app for evidence photos, then write photo references in the relevant item notes.

## Data and privacy
The app has no server and sends no audit data anywhere by itself. A static host serves only the app files. Audit entries stay in the browser's local storage unless the user shares or downloads them.
