# Glamoura — Web SDK demo site

A single-page static storefront for **Glamoura**, a *fictional* beauty retailer used to demonstrate the Auxia JavaScript Web SDK. Not a real store.

Three elements on the page are designated Auxia web-SDK **surface anchors** (`#auxia-hero-promo`, `#auxia-feed-card`, `#auxia-popup-root`), each holding the site's own default content. When the SDK is enabled for the project, decisioning personalizes those slots.

**Runtime config (URL params):** `?apiKey=` · `?userId=` · `?projectId=` · `?slots=1` (outline the surfaces) · `?nopopup=1`. The api key is never committed — pass it at runtime.

Static, no build step. Served via GitHub Pages.
