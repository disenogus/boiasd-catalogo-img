# boiasd-catalogo-img

Imágenes del catálogo de productos de Grupo BOIA S.D. (productos.boiasd.com), servidas vía jsDelivr.

- `productos/full/`  → 1200×1200 px, WebP (galería de la ficha de producto)
- `productos/thumb/` → 480×480 px, WebP (tarjetas del catálogo y miniaturas)

Nombre de archivo: `<código>-<nn>.webp` (ej. `10008-01.webp`). El `01` es la foto principal.

El catálogo apunta a una versión fija (commit) de este repositorio. Si se reemplaza o agrega una foto,
hay que actualizar `IMG_BASE` en `productos/productos-data.js` del catálogo con el nuevo commit.
