# Tipografía — HolyGrail 5

Las clases tipográficas se generan desde `config.typo`. Son mobile-first: los valores base aplican a mobile y `@media (min-width: 992px)` sobrescribe para desktop.

## Clases disponibles

```html
<h2 class="hg-h2">Título principal (18px mobile → 24px desktop)</h2>
<h3 class="hg-title-l-b">Título bold uppercase (14px)</h3>
<h3 class="hg-title-l">Título light (14px)</h3>
<h4 class="hg-title-m">Título medium (12px)</h4>
<h4 class="hg-title-s">Título small (12px, weight 400)</h4>

<p class="hg-text-l">Texto large (12px, light)</p>
<p class="hg-text-m">Texto medium (12→13px responsive)</p>
<p class="hg-semantic">Semántico (13px)</p>
<span class="hg-p-tag">Tag pequeño (8px)</span>

<p class="hg-suisse-1">Suisse 1 — fuente secundaria (16→20px)</p>
<p class="hg-suisse-2">Suisse 2 — fuente secundaria (13→14px)</p>
<p class="hg-suisse-body">Suisse body — fuente secundaria (10→12px)</p>

<p class="hg-hg-body-m">Body medium (12→13px)</p>
<p class="hg-hg-body-m-b">Body medium bold (weight 400)</p>
```

## Cómo funciona el CSS generado

```css
.hg-h2 {
  font-family: var(--hg-typo-font-family-primary-regular);
  font-weight: var(--hg-typo-font-weight-900);
  font-size: var(--hg-typo-font-size-18);
  line-height: var(--hg-typo-line-height-1-976);
}

@media (min-width: 992px) {
  .hg-h2 {
    font-size: var(--hg-typo-font-size-24);
    line-height: var(--hg-typo-line-height-1-2);
  }
}
```
