# Nettsider Bergen — Netlify deploy package

Upload THIS FOLDER to Netlify Drop.

Expected public URLs after the custom domain is connected:
- https://studio.tailoredomics.com/
- https://studio.tailoredomics.com/en/
- https://studio.tailoredomics.com/demo/klassisk-stil/

Important:
- `/demo/*` is protected from indexing both by page metadata and Netlify `X-Robots-Tag` headers.
- Add new previews as `demo/<slug>/index.html`, then redeploy the same folder.
- Do not link demo pages from the public landing page.
- Public prices are 5,999 / 6,999 NOK. The cold-email pilot offer remains private.
