Café Raíz

Sitio web responsivo, semántico y accesible para una cafetería ficticia de Monterrey, Nuevo León.
Proyecto de la **Actividad 2** del Laboratorio de Programación Web (FIME, UANL).

Objetivo
Construir y publicar un sitio web sencillo con HTML5 semántico y CSS moderno, que se vea correctamente tanto en computadora como en teléfono móvil, aplicando principios básicos de usabilidad, accesibilidad y validación de estándares.

Tecnologías usadas
- HTML5 (etiquetas semánticas).
- CSS3 con Flexbox (encabezado, navegación, tarjetas de productos, formulario) y **Grid** (portada y contacto).
- Git y GitHub Pages para publicar el sitio.

No se utiliza JavaScript, frameworks ni librerías externas.

Estructura de archivos

```text
cafe-raiz/
├── index.html        Inicio
├── servicios.html    Productos
├── contacto.html     Contacto (formulario)
├── style.css         Hoja de estilos única
├── README.md
├── img/
│   ├── foto1.jpg     Área de mesas
│   ├── foto2.jpg     Taza de café
│   └── foto3.jpg     Pan dulce
└── capturas/         Capturas de pantalla y validaciones
```

Cumplimiento de la actividad

| Requisito | Cómo se cumple |
|---|---|
| Mínimo 3 vistas | Inicio, Productos y Contacto |
| Etiquetas semánticas | header, nav, main, section, article y footer`en todas las páginas |
| Flexbox y/o Grid | Flexbox en encabezado, navegación, productos y formulario; Grid en portada y contacto. No se usan tablas para el diseño |
| Diseño responsivo | Breakpoint en max-width: 700px: las columnas pasan a una sola, el encabezado se apila y se agrega <meta name="viewport">. Se comprobó sin desbordes horizontales en anchos de 320, 390, 768 y 1280 px |
| Accesibilidad | Textos alternativos (alt) en todas las imágenes, label asociado a cada campo del formulario, jerarquía de encabezados (un h1 por página, luego h2), navegación con aria-label y aria-current, enlace "Saltar al contenido", foco visible con teclado y contraste mínimo de 5.19:1 (WCAG pide 4.5:1) |
| Validación | Ver sección de resultados |
| Publicación | Ver sección "Sitio publicado" |

Capturas

Escritorio (1280 px)

Inicio

Inicio en escritorio(capturas/inicio-escritorio.png)

Productos

!Productos en escritorio(capturas/productos-escritorio.png)

Contacto

Contacto en escritorio(capturas/contacto-escritorio.png)

Móvil (390 px)

Inicio

Inicio en móvil(capturas/inicio-movil.png)

Productos

Productos en móvil(capturas/productos-movil.png)

Contacto

Contacto en móvil(capturas/contacto-movil.png)

Resultados de validación

Validador HTML (W3C)
Validador: <https://validator.w3.org/>. Se validaron las tres páginas.

index.html

Validación HTML de index(capturas/validacion-html-inicio.png)

servicios.html

Validación HTML de servicios(capturas/validacion-html-productos.png)

contacto.html

Validación HTML de contacto(capturas/validacion-html-contacto.png)

Validador CSS (W3C)
Validador: <https://jigsaw.w3.org/css-validator/>.

Validación CSS(capturas/validacion-css.png)

Sitio publicado

Sitio publicado: [PENDIENTE: pegar aquí la liga de GitHub Pages]

