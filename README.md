# Autoescola Taradell — Sitio Web Oficial

Sitio web profesional de alta conversión para **Autoescola Taradell** (Carrer de Sant Sebastià, 37 · 08552 Taradell, Barcelona), centro de formación vial en la comarca de Osona desde **1983**.

## Estructura del Proyecto

```text
├── index.html          # Landing page editorial autocontenida (HTML5 + CSS3 + JS)
├── assets/             # Logotipo oficial, favicon, flota real y galería de aprobados
├── docs/               # Documentación estratégica (dossie_autoescola.md)
├── vercel.json         # Cabeceras de seguridad HTTP y caché de assets
├── robots.txt          # Directivas para buscadores (excluye /docs/)
├── sitemap.xml         # Mapa del sitio para SEO
└── .gitignore          # Exclusión de archivos temporales, secretos y notas locales
```

## Seguridad y Rendimiento

- Cabeceras HTTP configuradas en `vercel.json`: `Strict-Transport-Security`, `X-Content-Type-Options: nosniff`, `X-Frame-Options: SAMEORIGIN`, `Referrer-Policy` y `Permissions-Policy`.
- Enlaces externos con `rel="noopener noreferrer"`.
- Imágenes reales optimizadas con `loading="lazy"` en galería y caché inmutable de 1 año en `/assets/`.
