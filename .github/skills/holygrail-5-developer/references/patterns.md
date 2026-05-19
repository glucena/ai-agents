# Patrones comunes — HolyGrail 5

## Card de producto

```html
<div class="row hg-gap-16">
  <div class="col-xs-12 col-md-6">
    <div class="hg-aspect hg-aspect-2-3">
      <img class="hg-aspect-image" src="product.jpg" alt="Producto">
    </div>
  </div>
  <div class="col-xs-12 col-md-6 hg-d-flex hg-flex-column hg-justify-center hg-gap-8">
    <h2 class="hg-title-l-b">Nombre del producto</h2>
    <p class="hg-text-m" style="color: var(--hg-color-dark-grey)">Descripción corta.</p>
    <span class="hg-h2" style="color: var(--hg-color-primary)">49,90 €</span>
  </div>
</div>
```

## Hero centrado

```html
<section class="hg-d-flex hg-items-center hg-justify-center hg-min-h-100vh hg-text-center p-24">
  <div>
    <h1 class="hg-h2">Bienvenido</h1>
    <p class="hg-suisse-1" style="color: var(--hg-color-dark-grey)">Subtítulo descriptivo</p>
  </div>
</section>
```

## Grid de cards

```html
<div class="row hg-gap-16">
  <div class="col-xs-12 col-sm-6 col-lg-4 mb-16">
    <div class="hg-aspect hg-aspect-16-9">
      <img class="hg-aspect-image" src="img1.jpg" alt="">
    </div>
    <div class="pt-8">
      <h3 class="hg-title-l-b">Título card</h3>
      <p class="hg-text-m">Descripción breve.</p>
    </div>
  </div>
</div>
```

## Navbar sticky

```html
<header class="hg-position-sticky hg-z-50 hg-d-flex hg-justify-between hg-items-center p-16"
        style="top: 0; background: var(--hg-color-white); border-bottom: 1px solid var(--hg-color-middle-grey);">
  <span class="hg-title-l-b">Logo</span>
  <nav class="hg-d-flex hg-gap-24">
    <a class="hg-text-m" href="#">Inicio</a>
    <a class="hg-text-m" href="#">Productos</a>
  </nav>
</header>
```

## Layout sidebar

```html
<div class="row">
  <aside class="col-xs-12 col-md-3 hg-d-none md:hg-d-block p-16"
         style="border-right: 1px solid var(--hg-color-middle-grey);">
    <nav class="hg-d-flex hg-flex-column hg-gap-8">
      <a class="hg-text-m" href="#">Sección 1</a>
      <a class="hg-text-m" href="#">Sección 2</a>
    </nav>
  </aside>
  <main class="col-xs-12 col-md-9 p-16 md:p-32">
    <h1 class="hg-h2">Contenido principal</h1>
  </main>
</div>
```

## Footer multicolumna

```html
<footer class="pt-48 pb-24" style="background: var(--hg-color-grey-ultra); color: var(--hg-color-white);">
  <div class="row hg-px-16 md:hg-px-32 hg-gap-24">
    <div class="col-xs-12 col-md-4">
      <h4 class="hg-title-l-b" style="color: var(--hg-color-white);">Empresa</h4>
      <p class="hg-text-m" style="color: var(--hg-color-middle-grey);">Descripción breve.</p>
    </div>
    <div class="col-xs-6 col-md-4">
      <h4 class="hg-title-l-b" style="color: var(--hg-color-white);">Enlaces</h4>
    </div>
    <div class="col-xs-6 col-md-4">
      <h4 class="hg-title-l-b" style="color: var(--hg-color-white);">Legal</h4>
    </div>
  </div>
</footer>
```
