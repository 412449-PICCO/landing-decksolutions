# Assets — Deck Solutions

Todas las imágenes de esta carpeta son **placeholders generados**. Reemplazalas por las fotos
reales manteniendo exactamente el mismo nombre de archivo y una relación de aspecto similar.

| Archivo | Uso | Proporción sugerida |
|---|---|---|
| `logo.png` | Logo circular (navbar + footer + favicon) | 1:1 · 512×512 |
| `hero.jpg` | Fondo del hero + Open Graph. Deck de noche con la luz cálida en la pared | 16:9 · 1920×1080 |
| `reel-1..4.jpg` | Poster de los 4 reels verticales | 9:16 · 900×1600 |
| `sistema-01.jpg` | Estructura de caños de acero inoxidable | 4:3 |
| `sistema-02.jpg` | Detalle de las tablas de deck (eucalipto / Grandis) | 4:3 |
| `obra-1..6.jpg` | Galería "Nuestro trabajo" (1 y 5 son verticales) | 4:5 y 4:3 |
| `medida.jpg` | Bloque "Fabricados a medida", foto vertical del deck cerrado | 4:5 |
| `cta.jpg` | Fondo de la franja CTA, deck de día | 16:9 |

## Videos de los reels

Los `<video>` de la franja de reels tienen el `<source>` comentado en `index.html`.
Poné los archivos como `assets/reel-1.mp4` … `reel-4.mp4` (vertical 9:16, sin audio) y
descomentá la línea correspondiente:

```html
<source src="assets/reel-1.mp4" type="video/mp4">
```

## Otros pendientes de contenido real
- Teléfono de WhatsApp: hoy está `+54 9 223 123-4567` (constante `WA` en el `<script>` y links del footer/contacto).
- Email: `info@decksolutions.com.ar`.
- Mapa: el `<iframe>` de Google Maps está comentado en la sección Contacto.
