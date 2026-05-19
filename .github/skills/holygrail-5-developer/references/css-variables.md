# Variables CSS — HolyGrail 5

HolyGrail 5 genera variables CSS en `:root`. **Nunca hardcodees valores — usa siempre las variables.**

## Colores

Definidos en `config.colors`. Cada color genera `--hg-color-{nombre}`.

```css
color: var(--hg-color-primary);
background: var(--hg-color-bg-cream);
border-color: var(--hg-color-error);
```

Colores disponibles por defecto:

| Variable | Uso |
|----------|-----|
| `--hg-color-white` / `--hg-color-black` | Base |
| `--hg-color-dark-grey` / `--hg-color-middle-grey` / `--hg-color-light-grey` / `--hg-color-grey-ultra` | Escala de grises |
| `--hg-color-orange` / `--hg-color-mustard` | Acentos cálidos |
| `--hg-color-primary` | Color principal de marca |
| `--hg-color-error` / `--hg-color-info` / `--hg-color-success` / `--hg-color-warning` | Estados |
| `--hg-color-feel` / `--hg-color-feel-dark` | Emocional |
| `--hg-color-silver` / `--hg-color-gold` / `--hg-color-platinum` | Premium |
| `--hg-color-bg-light` / `--hg-color-bg-cream` | Fondos |

## Spacing

Definido en `config.spacingMap`. Cada valor genera `--hg-spacing-{key}`.

```css
--hg-spacing-0: 0;
--hg-spacing-4: 0.25rem;
--hg-spacing-8: 0.5rem;
--hg-spacing-16: 1rem;
--hg-spacing-24: 1.5rem;
--hg-spacing-32: 2rem;
/* ... hasta 160 */
--hg-spacing-50-percent: 50%;
--hg-spacing-100-percent: 100%;
```

Los valores px se convierten automáticamente a rem (base 16px).

## Tipografía

```css
--hg-typo-font-family-primary-regular: arial, sans-serif;
--hg-typo-font-family-secondary: "ms-serif", serif;
--hg-typo-font-size-12: 0.75rem;
--hg-typo-font-size-14: 0.875rem;
--hg-typo-font-size-24: 1.5rem;
--hg-typo-line-height-1-2: 1.2;
--hg-typo-line-height-1-5: 1.5;
--hg-typo-font-weight-100: 100;
--hg-typo-font-weight-700: 700;
```
