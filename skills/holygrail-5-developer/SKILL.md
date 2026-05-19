---
name: holygrail-5-developer
description: Generates HTML and CSS code using the HolyGrail 5 design system. Trigger when asked to create layouts, components, or patterns using HolyGrail 5. Always consult the project's `config.json` before generating code to ensure you use the correct classes and values based on the configured design system.
license: MIT
metadata:
  author: Massimo Dutti 2026
  version: '1.0'
---

# HolyGrail 5 — Guía de maquetación

Sistema de clases CSS generado desde `config.json`. Consulta siempre el config del proyecto antes de maquetar: las clases disponibles dependen de lo que esté configurado.

## Reglas fundamentales

1. **Mobile-first**: las clases base son para mobile, `md:` para desktop
2. **Nunca hardcodees valores**: usa `var(--hg-color-*)` y `var(--hg-spacing-*)`
3. **Valida contra config.json**: si un valor no está en `spacingMap`, no tendrá clase
4. **RTL-safe**: usa `.hg-px-*`, `.hg-py-*`, `.hg-mx-*`, `.hg-my-*` (usan `inline`/`block`)
5. **Prefijos**: spacing sin prefijo (`.p-*`, `.m-*`), helpers con prefijo (`.hg-d-flex`)
6. **Grid es flex**: `.row` + `.col-{bp}-{n}`, no CSS Grid nativo

## Instalación y configuración

Para instalar HolyGrail 5, importar el CSS o generar CSS personalizado: [installation.md](references/installation.md)

## Variables CSS

HolyGrail 5 genera variables en `:root` para colores, spacing y tipografía. Úsalas siempre en lugar de valores hardcodeados: [css-variables.md](references/css-variables.md)

## Spacing (padding y margin)

Clases `.p-*`, `.m-*` y variantes (top, bottom, inline, block). Incluye variantes responsive `md:` e `!important`: [spacing.md](references/spacing.md)

## Helpers de layout

Clases `hg-` para display, flexbox, alineación, gap, dimensiones, posicionamiento, overflow, visibilidad, cursor y object-fit: [layout-helpers.md](references/layout-helpers.md)

## Tipografía

Clases tipográficas mobile-first generadas desde `config.typo` (`hg-h2`, `hg-title-l-b`, `hg-text-m`, `hg-suisse-1`, etc.): [typography.md](references/typography.md)

## Grid

Sistema de columnas flexbox con breakpoints xs/sm/md/lg/xl. Clases `.row` y `.col-{bp}-{n}`: [grid.md](references/grid.md)

## Aspect Ratios

Contenedores con proporción fija. Clases `.hg-aspect`, `.hg-aspect-image`, `.hg-aspect-content` y ratios 1:1, 16:9, 2:3, etc.: [aspect-ratios.md](references/aspect-ratios.md)

## Patrones comunes

Ejemplos de card de producto, hero, grid de cards, navbar sticky, sidebar y footer: [patterns.md](references/patterns.md)

