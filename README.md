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

## Demo

El proyecto está disponible online para visualizar la maquetación responsive y comprobar su adaptación a distintos tamaños de pantalla.

[Ver demo](https://portfolio-layout-jonas.netlify.app/)

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
```

## Desarrollo

Para ejecutar el proyecto en local:

```bash
npm install
npm run dev
```

## Sobre el proyecto

Este proyecto está centrado principalmente en la maquetación y los estilos.

JavaScript no contiene lógica de aplicación; se utiliza únicamente como punto de entrada para cargar los estilos SCSS mediante Vite.

El contenido mostrado pertenece al diseño ficticio utilizado para realizar el ejercicio y no representa mi experiencia profesional personal.
