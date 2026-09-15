# Karenza

Sitio de demostración de una tienda de moda, en español y adaptable a móviles y computadoras.

## Contenido

- Catálogo de 249 productos, colecciones y páginas de producto.
- Búsqueda, filtros, selección de variantes y vista rápida.
- Carrito guardado en el navegador.
- Imágenes y fuentes incluidas en `dist/assets/`.

## Ejecutar en tu computadora

Con Python 3 instalado, abre una terminal en esta carpeta y ejecuta:

```sh
python -m http.server 8080 --directory dist
```

Abre **http://localhost:8080**. El sitio debe abrirse mediante un servidor HTTP para cargar el catálogo correctamente.

## Estructura

- `dist/index.html`: página de inicio.
- `dist/app.js`: navegación e interacciones.
- `dist/style.css` y `dist/details.css`: diseño y estilos.
- `dist/catalog.json`, `dist/collections.json` y `dist/sections.json`: catálogo y contenido.
- `dist/products/`, `dist/collections/` y `dist/pages/`: páginas con rutas propias.

## Alojamiento

Publica el contenido de `dist/` en la raíz de un alojamiento estático. Las rutas actuales parten de `/`; para alojarlo en un subdirectorio como `/Karenza/`, primero hay que adaptar esas rutas.

## Estado de la tienda

Esta versión es una demostración. Los pagos, las cuentas de clientes y las suscripciones no están conectados a servicios reales. Los productos, precios, marcas y dirección comercial son contenido de referencia y deben revisarse antes de abrir una tienda real.

## Referencia visual

El diseño se basa en la [demostración Dune del tema Impulse](https://themes.shopify.com/themes/impulse/presets/dune?locale=es). Las fotografías, las fuentes y las marcas de terceros conservan los derechos de sus respectivos titulares. Este repositorio no incluye una licencia comercial del tema Shopify.
