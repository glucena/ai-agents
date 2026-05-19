# Aspect Ratios — HolyGrail 5

## Uso

```html
<div class="hg-aspect hg-aspect-2-3">
  <img class="hg-aspect-image" src="foto.jpg" alt="">
</div>

<div class="hg-aspect hg-aspect-16-9">
  <img class="hg-aspect-image" src="video-thumb.jpg" alt="">
</div>

<div class="hg-aspect hg-aspect-4-3">
  <div class="hg-aspect-content">
    <h3 class="hg-title-l-b">Texto sobre imagen</h3>
  </div>
</div>
```

## Ratios disponibles

| Clase | Ratio | Uso típico |
|-------|-------|-----------|
| `.hg-aspect` | 2:3 | Default vertical |
| `.hg-aspect-1-1` | 1:1 | Avatar, cuadrado |
| `.hg-aspect-4-3` | 4:3 | Foto tradicional |
| `.hg-aspect-16-9` | 16:9 | Video, widescreen |
| `.hg-aspect-2-1` | 2:1 | Banner doble ancho |
| `.hg-aspect-2-3` | 2:3 | Vertical |
| `.hg-aspect-3-4` | 3:4 | Vertical |
| `.hg-aspect-3-1` | 3:1 | Separador XL |
| `.hg-aspect-7-1` | 7:1 | Separador LG |
| `.hg-aspect-12-1` | 12:1 | Separador MD |
| `.hg-aspect-24-1` | 24:1 | Separador SM |
| `.hg-aspect-9-20` | 9:20 | Vertical móvil |
| `.hg-aspect-16-4` | 16:4 | Banner |

## Clases auxiliares

- `.hg-aspect-image` — para `<img>` y `<video>`: `display: block; width: 100%; height: 100%; object-fit: cover`
- `.hg-aspect-content` — contenido posicionado: `position: absolute; inset: 0`
