# Instalación — HolyGrail 5

## npm

```bash
npm install holygrail5
```

## Importar el CSS

**HTML directo:**
```html
<link rel="stylesheet" href="node_modules/holygrail5/dist/output.css">
```

**Bundler (Vite, Webpack, etc.):**
```js
import 'holygrail5/dist/output';
```

**Con tema Dutti** (importar después del base):
```js
import 'holygrail5/dist/output';
import 'holygrail5/dist/dutti';
```

**CodePen / playground online:**
```html
<link rel="stylesheet" href="https://unpkg.com/holygrail5/dist/output.css">
<link rel="stylesheet" href="https://unpkg.com/holygrail5/dist/themes/dutti.css">
```
En CodePen: **Settings → CSS → Add External Stylesheets**.

## Generar CSS personalizado

```bash
cp node_modules/holygrail5/config.json ./hg5-config.json
# Editar hg5-config.json con tus valores
npx holygrail5
```

Genera `dist/output.css` con las clases adaptadas a tu configuración.

## Watch mode

```bash
npm run dev
```
