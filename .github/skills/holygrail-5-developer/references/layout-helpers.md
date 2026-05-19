# Layout Helpers — HolyGrail 5

Todos los helpers llevan el prefijo `hg-`. Se configuran en `config.helpers`. Cada uno puede tener variante responsive `md:`.

## Display

```html
<div class="hg-d-flex">Flex</div>
<div class="hg-d-block">Block</div>
<div class="hg-d-none">Oculto</div>
<div class="hg-d-inline-block">Inline block</div>
<div class="hg-d-inline-flex">Inline flex</div>
<div class="hg-d-contents">Contents</div>

<div class="hg-d-none md:hg-d-block">Solo desktop</div>
```

## Flexbox

```html
<div class="hg-flex-row">Horizontal</div>
<div class="hg-flex-column">Vertical</div>
<div class="hg-flex-wrap">Wrap</div>
<div class="hg-flex-nowrap">No wrap</div>
<div class="hg-grow-1">Crece</div>
<div class="hg-shrink-0">No encoge</div>
<div class="hg-flex-1">flex: 1 1 0%</div>
<div class="hg-flex-auto">flex: 1 1 auto</div>
<div class="hg-flex-none">flex: none</div>
<div class="hg-basis-auto">Basis auto</div>
<div class="hg-basis-full">Basis 100%</div>
<div class="hg-order-1">Orden 1</div>
<div class="hg-order-first">Primero (-9999)</div>
<div class="hg-order-last">Último (9999)</div>
```

## Alineación

```html
<div class="hg-d-flex hg-justify-start">Inicio</div>
<div class="hg-d-flex hg-justify-center">Centro</div>
<div class="hg-d-flex hg-justify-end">Final</div>
<div class="hg-d-flex hg-justify-between">Space between</div>
<div class="hg-d-flex hg-justify-around">Space around</div>
<div class="hg-d-flex hg-justify-evenly">Space evenly</div>

<div class="hg-d-flex hg-items-start">Arriba</div>
<div class="hg-d-flex hg-items-center">Centro vertical</div>
<div class="hg-d-flex hg-items-end">Abajo</div>
<div class="hg-d-flex hg-items-baseline">Baseline</div>
<div class="hg-d-flex hg-items-stretch">Stretch</div>

<div class="hg-d-flex hg-flex-wrap hg-content-center">Align content centro</div>
```

## Gap (usa spacingMap)

```html
<div class="hg-d-flex hg-gap-8">Gap 8px</div>
<div class="hg-d-flex hg-gap-16">Gap 16px</div>
<div class="hg-d-flex hg-gap-24">Gap 24px</div>
<div class="hg-d-flex hg-gap-y-16">Row gap 16px</div>
<div class="hg-d-flex hg-gap-x-8">Column gap 8px</div>
<div class="hg-d-flex hg-gap-8 md:hg-gap-24">Responsive gap</div>
```

## Dimensiones

```html
<div class="hg-w-100-percent">100%</div>
<div class="hg-w-50-percent">50%</div>
<div class="hg-w-auto">Auto</div>
<div class="hg-w-fit-content">Fit content</div>
<div class="hg-w-100vw">100vw</div>
<div class="hg-h-100-percent">100%</div>
<div class="hg-h-100vh">100vh</div>
<div class="hg-h-100dvh">100dvh (dynamic)</div>
<div class="hg-h-auto">Auto</div>
<div class="hg-min-h-100vh">Min 100vh</div>
<div class="hg-min-h-100dvh">Min 100dvh</div>
```

## Posicionamiento

```html
<div class="hg-position-relative">Relative</div>
<div class="hg-position-absolute">Absolute</div>
<div class="hg-position-fixed">Fixed</div>
<div class="hg-position-sticky">Sticky</div>
<div class="hg-z-10">z-index: 10</div>
<div class="hg-z-50">z-index: 50</div>
```

## Margin auto

```html
<div class="hg-mx-auto">Centrado horizontal</div>
<div class="hg-ml-auto">Alinear derecha</div>
<div class="hg-mr-auto">Alinear izquierda</div>
```

## Texto, overflow, visibilidad, cursor, object-fit

```html
<div class="hg-text-left">Izquierda</div>
<div class="hg-text-center">Centro</div>
<div class="hg-text-right">Derecha</div>
<div class="hg-text-justify">Justificado</div>

<div class="hg-overflow-hidden">Hidden</div>
<div class="hg-overflow-auto">Auto</div>
<div class="hg-overflow-x-auto">Scroll horizontal</div>
<div class="hg-overflow-y-hidden">Sin scroll vertical</div>

<div class="hg-visibility-hidden">Invisible (ocupa espacio)</div>
<div class="hg-opacity-0">Transparente</div>
<div class="hg-opacity-50">50% opacidad</div>
<div class="hg-opacity-100">Totalmente visible</div>

<div class="hg-cursor-pointer">Pointer</div>
<div class="hg-cursor-not-allowed">No permitido</div>
<div class="hg-cursor-grab">Grab</div>
<div class="hg-pointer-events-none">Sin eventos</div>

<img class="hg-object-cover" src="..." alt="">
<img class="hg-object-contain" src="..." alt="">
```
