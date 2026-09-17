# webpulsar

Código del tema de Shopify de [webpulsar.es](https://webpulsar.es) (tienda `webpulsar`), exportado desde el tema
"WebPulsar - Mejoras mantenimiento y whatsapp (preview)" en el admin de Shopify.

## Estructura

Estructura estándar de un tema de Shopify (Online Store 2.0): `assets/`, `config/`, `layout/`, `locales/`,
`sections/`, `snippets/`, `templates/`.

## Nota sobre assets binarios

La fuente `assets/clash-display-variable.woff2` no se incluyó en este export porque no se pudo transferir de forma
fiable en el proceso de subida. El resto de assets (CSS, JS, la otra fuente variable y el SVG de grano) sí están
completos. Para tener el tema 100% completo en Git, lo más fiable es usar `shopify theme pull` (Shopify CLI) desde
esta carpeta con la tienda autenticada.

## Cómo aplicar cambios al tema real

Este repo es una copia del código. Para probar o publicar cambios en Shopify:
1. Sube los archivos a un tema nuevo o sin publicar (`shopify theme push` o desde el editor de temas del admin).
2. Pruébalo con el enlace de preview del tema.
3. Publícalo desde el admin de Shopify cuando estés conforme.
