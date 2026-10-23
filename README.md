# client-pages

Client landing and authority pages, hosted on Vercel (team Kodara CSM) and shown on each
client's own GHL page through a small iframe snippet. Approved by Lucas 2026-10-23.

- One folder per client, one subfolder per page: `<client>/<page>/index.html` (+ its `styles.css`).
- A push to `main` deploys. The client's GHL page shows the change within a minute; no GHL edit needed.
- Links that leave the page use `target="_top"` so checkouts open full-window, not inside the iframe.
- Each page posts its height to the parent (`kodaraPageHeight`) so the GHL snippet can size the iframe.
- If a client leaves: inline `styles.css` into the page and paste the full HTML into their own GHL.

| Client | Page | Live on | Hosted path |
|---|---|---|---|
| Alisa Larsen | 3-offer page | playfulsinger.com/start | /alisa-larsen/start/ |
