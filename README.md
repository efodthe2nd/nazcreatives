# NazCreatives — Framer site export

This is a static capture of the published NazCreatives Framer website, arranged for a GitHub Pages repository.

## Preview locally

Because the site uses JavaScript modules, open a terminal in this folder and run one of:

- Python: `python -m http.server 8000`
- Node (if installed): `npx serve .`

Then visit `http://localhost:8000`.

## Deploy to GitHub Pages

1. Create a GitHub repository and upload/push the contents of this folder (the `index.html` file must be at the repository root).
2. In the repository, open **Settings → Pages**.
3. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
4. Add your custom domain in the Pages settings after the GitHub Pages URL works.
5. Add the DNS records GitHub Pages specifies at your domain registrar, then enable HTTPS when available.

## Notes

This is a captured production build, not the original editable Framer project. The layout, assets, and Framer runtime have been preserved where included in the export. Some tracking/edit-only resources may be unnecessary. Test all pages, links, forms, mobile layouts, and animations before switching your domain. A static host cannot run server-side functionality.
