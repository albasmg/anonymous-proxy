# Evaluación final

Evaluación final del módulo I en Adalab. Se trata de una web app realizada con HTML y CSS (SCSS) partiendo de la estructura del Adalab Web Starter Kit.

### Cómo instalar

```
npm install
```

### Cómo arrancar el proyecto

```
npm start
```

### Cómo publicar el proyecto en producción

```
npm run docs
```

## Estructura de carpetas y ficheros

La estructura de las carpetas y ficheros que he elegido es la siguiente:

```
src
 ├─ html
 |  ├─ index.html
 |  └─ partials
 |     ├─ header.html
 |     ├─ main.html
 |     ├─ footer.html
 |     └─ reasons-to-purchase.html
 |
 ├─ scss
 |  ├─ components
 |  |    └─ _button.scss
 |  ├─ core
 |  |   ├─ _variables.scss
 |  |   ├─ _reset.scss
 |  |   └─ _mixins.scss
 |  ├─ layout
 |  |   ├─ _header.scss
 |  |   ├─ _footer.scss
 |  |   └─ _page.scss
 |  └─ pages
 |
 └─ images

```

## HTML

Se ha dividido el HTML en cuatro partials:

#### Header

Incluye el icono del menú, aunque este tiene una posición fija y se mantiene en el lado izquierdo en la parte superior aunque se haga scroll en la página. Al pulsar sobre el icono no se despliega ningún menú, sino que te lleva a la página de Adalab, que se abre en otra pestaña.
Un botón situado al pie de la imagen te lleva a la sección de razones para comprar.

### Main

Incluye las secciones de información y razones para comprar. La primera maquetada con flexbox y la segunda usando grid.

#### Reasons-to-purchase

Se trata de un motor de plantillas que permite reutilizar el código en una de las secciones del main.

### Footer

Incluye dos menús de navegación. Al igual que el menú de navegación superior, todos los enlaces te llevan a la web de Adalab en otra pestaña. Maquetado usando flexbox. Un botón situado en la partes superior del footer te lleva a la home.

### CSS

Al igual que el HTML, los archivos SCSS en los que se han trabajado los estilos se han dividido en partes coincidiendo con el header, footer y main del html.

También se ha añadido una hoja de reset, unas variables para los colores, fuentes y breakpoints que se usan a lo largo de toda la web; y, unos mixins que permiten reutilizar partes de código que se repiten, como por ejemplo los mediaqueries.

Se ha creado un componente para los estilos de los botones de la web.
