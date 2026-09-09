# Assets — Deck Solutions

Las tres fotos del cliente, optimizadas (realce suave de contraste/color/nitidez, JPEG
progresivo de calidad 84). De cada una hay una versión grande y una de 800 px que se
sirve por `srcset` en pantallas chicas.

| Archivo | Dónde se usa |
|---|---|
| `deck-noche.jpg` | Fondo del hero (con parallax), tercera foto de la galería y Open Graph |
| `deck-pileta.jpg` | Primera foto de la galería (vertical grande) y bloque "Fabricados a medida" |
| `deck-casa.jpg` | Segunda foto de la galería y fondo de la franja CTA (con parallax) |

Originales en `~/Downloads` (`WhatsApp Image 2026-09-02 at 5.08.42 PM (3)/(4).jpeg` y
`WhatsApp Image 2026-09-07 at 11.44.38 AM.jpeg`).

## Sin imágenes inventadas

- No hay videos ni fotos de relleno: la franja de reels se eliminó.
- El logo es un SVG dibujado en línea (círculo + triángulo dorado), no un archivo. Si el
  cliente pasa el logo real, reemplazá los dos `<span class="marca">` del `index.html`
  (navbar y footer) por un `<img>` y actualizá el favicon del `<head>`.
- Los dos bloques técnicos de "El sistema" usan esquemas SVG dibujados a medida (corte de
  capas y corte del voladizo + detalle de tabla), no fotos.

## Para agregar más fotos a la galería

En la sección `#trabajo`, duplicá un `<figure class="gal-item">`. Las clases: `tall` ocupa
dos filas (para verticales), sin clase ocupa una (para apaisadas). El lightbox y el
revelado por scroll se enganchan solos.

## Datos de contacto cargados

- WhatsApp principal (todos los CTA): **+54 9 3515 09-0542** → `wa.me/5493515090542`
- Segundo WhatsApp (sección Contacto): **+54 9 2944 14-3318** → `wa.me/5492944143318`
- Ciudad: **Córdoba Capital**
- Email: **cubrepiscina.deck@gmail.com**
- Instagram: **@cubrepisicna.deck** (tal cual lo pasó el cliente; ojo que el mail dice "cubrepiscina", verificar cuál es)
- Facebook: sin cuenta confirmada, se quitó el ícono del footer
- Dominio `decksolutions.com.ar` en `canonical`/`og:url`: placeholder, cambiar por el real
- Mapa: el `<iframe>` de Google Maps está comentado en la sección Contacto

## Tipografía

- Títulos: **Fraunces** (serif variable, ejes SOFT/WONK/opsz)
- Interfaz y cuerpo: **Archivo**
