# Tatto-Maldo

Proyecto web responsive de Tatto-Maldo, desarrollado con HTML, Bootstrap y SCSS.

## Arquitectura SCSS

La hoja de estilos fue refactorizada utilizando un único punto de entrada:

```text
scss/
├── main.scss
├── utilities/
│   ├── _variables.scss
│   └── _mixins.scss
├── base/
│   ├── _tipografia.scss
│   └── _base.scss
├── layout/
│   ├── _header.scss
│   ├── _nav.scss
│   └── _footer.scss
└── components/
    ├── _buttons.scss
    ├── _cards.scss
    ├── _carousel.scss
    ├── _modal.scss
    └── _sections.scss
```

El archivo `styles/style.css` es el resultado compilado de `scss/main.scss`. No contiene estilos escritos manualmente como fuente del proyecto.

## Compilación

Instalar las dependencias:

```bash
npm install
```

Compilar SCSS a CSS:

```bash
npm run sass
```

Para trabajar en modo automático:

```bash
npm run watch
```
## 🌐 Sitio desplegado

[Ver Tatto-Maldo en Netlify](https://tatto-maldo.netlify.app)

