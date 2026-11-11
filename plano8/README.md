# Plano 8 — Productora audiovisual

Landing page estática (HTML + CSS + JS, sin dependencias ni build).

## Estructura

```
index.html          La página
og-image.jpg        Imagen que se ve al compartir el link (WhatsApp, Instagram, etc.)
assets/img/         Fotos, logo e íconos
assets/video/       Logo animado
vercel.json         Configuración de caché para Vercel
```

## Publicar

1. Subir esta carpeta a un repositorio de GitHub.
2. En vercel.com/new importar el repositorio. Framework Preset: **Other**. Dejar todo lo demás por defecto y apretar Deploy.
3. Cada vez que se haga un cambio en GitHub, Vercel republica solo.

## Después del primer deploy

En `index.html` reemplazar `TU-DOMINIO.vercel.app` por el link real (aparece 3 veces, en las etiquetas `og:url`, `og:image` y `twitter:image`). Sin esto la foto no aparece al compartir el link.

## Cambiar una foto

Reemplazar el archivo dentro de `assets/img/` por otro con **el mismo nombre**.
