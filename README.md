# HTB Writeups GitHub Page

## Estructura

```txt
.
├── index.html
├── assets/
│   ├── css/style.css
│   └── img/wallpaper.jpg
└── posts/
    ├── lab/
    │   ├── index.html
    │   └── example-protected.html
    ├── prolab/
    │   ├── index.html
    │   └── example-protected.html
    └── challenge/
        ├── index.html
        └── example-protected.html
```

## Importante

Los links usan `index.html` explícito para evitar que el navegador muestre el listado feo de carpetas en local.

## Fondo

Pon tu imagen aquí:

```txt
assets/img/wallpaper.jpg
```

Cambia la transparencia en `assets/css/style.css`:

```css
body::before {
  opacity: 0.34;
}
```

Más alto = fondo más visible. Más bajo = fondo más oscuro.

## Agregar posts

Guarda tus HTML cifrados en la categoría correcta:

```txt
posts/lab/jet.html
posts/prolab/zephyr.html
posts/challenge/web-baby.html
```

Después edita el `index.html` de esa carpeta y agrega una card:

```html
<a class="post-card" href="jet.html">
  <span>LOCKED</span>
  <h2>Jet</h2>
  <p>HTB Lab Writeup</p>
</a>
```
