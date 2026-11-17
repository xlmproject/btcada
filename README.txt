BTCADA Cloudflare Pages site

Files:
- index.html: responsive BTCADA landing page
- logo.png: generated BTCADA logo artwork
- stellar.toml: Stellar asset metadata

Deploy:
1. Upload/import this folder to Cloudflare Pages.
2. Add a custom static file route so stellar.toml is served at:
   https://btcada.pages.dev/.well-known/stellar.toml
   The simplest setup is to create a .well-known folder and place stellar.toml inside it.
3. Ensure logo.png is available at https://btcada.pages.dev/logo.png.
4. Replace the Trade BTCADA links with the exact asset trading URL once the asset is listed on your chosen exchange.

Important:
The displayed price is informational and hard-coded, not live market data.
The issuer address is reproduced exactly as supplied; verify it before publishing.
