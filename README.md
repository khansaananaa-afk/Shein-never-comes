# SHEIN NEVER COMES
SHOP EVERYTHING. EXPECT NOTHING.

Independent fictional shopping project. Not affiliated with SHEIN. No real payments, shipping or tracking.

- Single file: `index.html` (no build step, no dependencies)
- 1,050 sample products generated from data inside the file
- Cart, wishlist, orders and random delivery results are saved in the browser (localStorage)
- Map is an SVG drawing (no external tiles)

## Product photos
Products show built-in flat-lay illustrations by default. To use real photos (product-only, no female models),
put files in `images/`:
- `images/<productId>.jpg` (0-1049) for one specific product, or
- `images/<category>-<sub>.jpg` (e.g. `0-0.jpg` = Women > Dresses) for a whole subcategory.
Only use photos you have the rights to. Missing files fall back to the illustration automatically.

Deploy: GitHub Pages (Settings > Pages > main / root).
