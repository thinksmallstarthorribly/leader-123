# Leader 1-2-3 Sales Page Versions

## Version 2 — Current

The current sales page is the repository root [`../index.html`](../index.html). This placement ensures that the configured GitHub Pages/custom-domain deployment serves **V2** by default. A complete portable copy is stored in [`../sales-page-v2/`](../sales-page-v2/), including its local `images/pit-graphic.jpeg` asset.

V2 was imported from the approved source at `https://efxyhklx4394.space.mcode.io/` on 10 September 2026. The page is self-contained apart from Google Fonts and the established Stripe checkout link; its page image is stored in the repository so it does not rely on the temporary source host.

## Version 1 — Archived

The immediately preceding production root `index.html` is preserved byte-for-byte at [`../archive/sales-page-v1/index.html`](../archive/sales-page-v1/index.html). This archive is retained for historical reference and rollback; it is not the deployed default.

## Rollback

If a rollback is required, replace the root `index.html` with `archive/sales-page-v1/index.html` and commit the change. The historical file remains otherwise untouched.
