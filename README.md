# Karenza

Sitio de demostración de una tienda de moda, en español y adaptable a móviles y computadoras.

## Contenido

- Catálogo de 249 productos, colecciones y páginas de producto.
- Búsqueda, filtros, selección de variantes y vista rápida.
- Carrito guardado en el navegador.
- Imágenes y fuentes incluidas en `assets/`.

## Sitio publicado

https://albarini.github.io/Karenza/

## Ejecutar en tu computadora

Guarda este repositorio en una carpeta llamada `Karenza`. Con Python 3 instalado, abre una terminal en la carpeta que contiene `Karenza` y ejecuta:

```sh
python -m http.server 8080
```

Abre **http://localhost:8080/Karenza/**. El sitio debe abrirse mediante un servidor HTTP para cargar el catálogo correctamente.

## Estructura

- `index.html`: página de inicio.
- `app.js`: navegación e interacciones.
- `style.css` y `details.css`: diseño y estilos.
- `catalog.json`, `collections.json` y `sections.json`: catálogo y contenido.
- `products/`, `collections/` y `pages/`: páginas con rutas propias.

## Alojamiento

GitHub Pages publica la rama `main`, carpeta raíz (`/`). El archivo `index.html` es la entrada de la tienda y `.nojekyll` evita que se publique el README como sitio. Las rutas están adaptadas a `/Karenza/`. No se requiere un proceso de compilación ni dependencias.

## Estado de la tienda

Esta versión es una demostración. Los pagos, las cuentas de clientes y las suscripciones no están conectados a servicios reales. Los productos, precios, marcas y dirección comercial son contenido de referencia y deben revisarse antes de abrir una tienda real.

## Referencia visual

El diseño se basa en la [demostración Dune del tema Impulse](https://themes.shopify.com/themes/impulse/presets/dune?locale=es). Las fotografías, las fuentes y las marcas de terceros conservan los derechos de sus respectivos titulares. Este repositorio no incluye una licencia comercial del tema Shopify.
