# Order Archive

Embedded Shopify admin app for The SportScreen Ltd. that shows historical ShipStation and OrderSpace orders (2015–2025).

**This repository contains no customer or order data.** Order history is stored privately inside the Shopify store as app-owned metaobjects (`$app:order_archive_chunk`, storefront access: none) and is loaded only inside Shopify admin through App Bridge direct API access.

- `index.html` – the whole app (App Bridge + search UI + one-time importer)
- Shopify app: "Order Archive" in the Dev Dashboard; scopes `write_metaobject_definitions, write_metaobjects`

Do not commit data files (`*.json` exports) to this repository.
