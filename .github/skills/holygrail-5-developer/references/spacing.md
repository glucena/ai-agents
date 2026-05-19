# Spacing — HolyGrail 5

Las clases de spacing **no llevan prefijo `hg-`**. Se generan para cada valor en `config.spacingMap`.

## Padding

| Clase | Propiedad CSS |
|-------|--------------|
| `.p-{key}` | `padding` (4 lados) |
| `.pt-{key}` | `padding-top` |
| `.pb-{key}` | `padding-bottom` |
| `.pl-{key}` | `padding-inline-start` |
| `.pr-{key}` | `padding-inline-end` |
| `.hg-px-{key}` | `padding-inline` (horizontal) |
| `.hg-py-{key}` | `padding-block` (vertical) |

## Margin

| Clase | Propiedad CSS |
|-------|--------------|
| `.m-{key}` | `margin` (4 lados) |
| `.mt-{key}` | `margin-top` |
| `.mb-{key}` | `margin-bottom` |
| `.ml-{key}` | `margin-inline-start` |
| `.mr-{key}` | `margin-inline-end` |
| `.hg-mx-{key}` | `margin-inline` (horizontal) |
| `.hg-my-{key}` | `margin-block` (vertical) |

## Responsive

Todas las clases de spacing tienen variante desktop con prefijo `md:`:

```html
<div class="p-8 md:p-32">8px mobile, 32px desktop</div>
<div class="mb-0 md:mb-24">Sin margen mobile, 24px en desktop</div>
```

## Variante !important

Los keys en `spacingImportant` generan clases con `!important`:

```html
<div class="p-0!">Padding 0 con !important</div>
```
