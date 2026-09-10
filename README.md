# Leader 1-2-3

## Current sales page: V2

**`index.html` is the current production sales page (V2).** It is the page deployed at the repository’s configured custom domain, `leader123.com.au`.

The complete standalone V2 source is also retained in [`sales-page-v2/`](sales-page-v2/) so the version is explicit and portable. Its only local image asset is included at `sales-page-v2/images/pit-graphic.jpeg`; the deployed root page uses the equivalent `images/pit-graphic.jpeg` path.

| Version | Status | Location | Notes |
|---|---|---|---|
| V2 | **Current** | [`index.html`](index.html) and [`sales-page-v2/`](sales-page-v2/) | Current Leader 1-2-3 sales page. |
| V1 | Archived | [`archive/sales-page-v1/`](archive/sales-page-v1/) | Exact copy of the prior production root page, retained unchanged. |

## Repository layout

```text
index.html                    # Current production sales page (V2)
images/pit-graphic.jpeg       # V2 image asset used by the root deployment
sales-page-v2/                # Complete standalone V2 source and asset
archive/sales-page-v1/        # Preserved V1 sales page
portal.html                   # Student portal
access.html                   # Access page
module-1.html … module-8.html # Programme modules
docs/RAW_CONTENT.md           # Source and programme content notes
```

To preview V2 locally, serve the repository root with any static web server and open `index.html`. The V2 checkout links point to the existing Stripe payment URL.
