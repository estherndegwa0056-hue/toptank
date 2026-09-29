TOPTANK WEBSITE — CATEGORY IMAGES + CLEAN LAYOUT

Includes index.html, app.js, styles.css, hero assets, and local SVG fallback product illustrations under assets/images/.

The catalog is arranged to match the supplied reference: left filter sidebar, four products per row on desktop/tablet, and two columns on mobile. Product names and prices sit beneath evenly sized images. The TopTank Products heading and View All Products link remain on one line.

Remote image URLs are preserved. If a remote image cannot load, a bundled local category/product illustration appears instead of a broken image.

To publish: extract this ZIP and upload all contents of the toptank_site folder to your hosting root. Keep index.html, app.js, styles.css, and the assets folder together.

Image fix: product images use URL-safe local filenames in assets/ to avoid spaces/commas breaking paths. Product image mapping is in app.js under LOCAL_PRODUCT_IMAGES.
