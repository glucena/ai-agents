# Grid — HolyGrail 5

Se activa con `grid.enabled: true` en `config.json`. Sistema de columnas flexbox — **no es CSS Grid nativo**.

## Breakpoints

| Breakpoint | Min-width | Columnas |
|-----------|-----------|----------|
| `xs` | 1px | 12 |
| `sm` | 768px | 12 |
| `md` | 992px | 12 |
| `lg` | 1280px | 12 |
| `xl` | 1440px | 24 |

## Uso básico

```html
<div class="row">
  <div class="col-xs-12 col-md-6">Mitad en desktop</div>
  <div class="col-xs-12 col-md-6">Mitad en desktop</div>
</div>

<div class="row">
  <div class="col-xs-12 col-md-4">Tercio</div>
  <div class="col-xs-12 col-md-4">Tercio</div>
  <div class="col-xs-12 col-md-4">Tercio</div>
</div>

<div class="row">
  <aside class="col-xs-12 col-lg-3">Sidebar</aside>
  <main class="col-xs-12 col-lg-9">Contenido</main>
</div>

<div class="row">
  <div class="col-xl-8">8 de 24 (XL)</div>
  <div class="col-xl-16">16 de 24 (XL)</div>
</div>
```

## Bleed (sin gutter)

```html
<div class="row bleed">
  <div class="col-md-6">Sin padding lateral</div>
  <div class="col-md-6">Sin padding lateral</div>
</div>
```

## Propiedades

- Gutter: `8px` (padding lateral por columna)
- Container margin: `16px`
- `.row` → `display: flex; flex-wrap: wrap` con márgenes negativos
