# Portfolio Layout

Proyecto académico de maquetación responsive de un portfolio ficticio, desarrollado como parte de mi formación en desarrollo web.

El objetivo del proyecto fue reproducir una interfaz completa adaptada a distintos tamaños de pantalla, trabajando especialmente la organización de estilos con Sass/SCSS y el diseño responsive.

## Tecnologías

- HTML5
- Sass / SCSS
- Vite

## Características

- Diseño responsive para móvil, tablet y escritorio.
- Organización modular de estilos con Sass.
- Uso de variables y mixins reutilizables.
- Breakpoints personalizados para adaptar la interfaz.
- Grid y Flexbox para la distribución de los elementos.
- Estados hover en enlaces y proyectos.
- Formulario de contacto maquetado con validación visual mediante CSS.
- Uso de elementos semánticos y atributos de accesibilidad.

## Estructura de estilos

Los estilos están organizados en diferentes módulos:

```text
src/styles/
├── abstracts/
│   ├── _mixins.scss
│   ├── _utilities.scss
│   └── _variables.scss
│
├── components/
│   ├── _buttons.scss
│   ├── _footer.scss
│   ├── _header.scss
│   ├── _hero.scss
│   └── _information.scss
│
└── main.scss
