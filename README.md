# Portafolio web — José Fausto Salas Fajardo

Sitio personal estático para presentar formación, habilidades y proyectos académicos. Está construido con HTML semántico, CSS responsive y JavaScript sin dependencias de framework.

## Archivos

- `index.html`: estructura y contenido del sitio.
- `styles.css`: diseño visual, Flexbox, Grid, media queries, modo claro/oscuro y foco visible.
- `script.js`: traducción ES/EN/FR, menú móvil, tema y año del footer.
- `assets/foto-245.webp` y `foto-490.webp`: tu foto en dos tamaños (`srcset`).
- `assets/certificados/`: los 5 certificados en PDF y sus miniaturas WebP (480 y 960 px).
- `assets/cv-fausto-salas.pdf`: currículum descargable.
- `assets/favicon.svg`: icono del sitio.
- `CHECKLIST.md`: lista de autoevaluación para la rúbrica.

## Cómo verlo localmente

1. Descarga y descomprime el ZIP.
2. Abre `index.html` en un navegador moderno.
3. Para una prueba más parecida a producción, usa la extensión **Live Server** de Visual Studio Code o ejecuta un servidor HTTP local.

El sitio utiliza Google Fonts como mejora visual; si no hay conexión, se mostrarán fuentes alternativas del sistema.

## Accesibilidad y funcionamiento

- Enlace para saltar al contenido, etiquetas semánticas, textos alternativos, controles etiquetados y foco visible.
- Menú móvil con estado `aria-expanded`.
- Respeta `prefers-reduced-motion`.
- Traducciones para español, inglés y francés.
- Modo claro/oscuro e idioma se recuerdan entre visitas (localStorage con manejo de errores).
- Los enlaces de GitHub, LinkedIn y correo usan los datos proporcionados; no se inventan demos ni certificaciones.

## Nota sobre contenido

SRIU se presenta como un prototipo académico con vistas para alumnos y administradores. 

PixelShop se describe como proyecto académico de tienda en línea. Las imágenes de las tarjetas son ilustraciones decorativas, no capturas de sistemas publicados.

## Rediseño "After Hours" (versión 4)

Paleta carbón/marfil/vino, Fraunces (títulos) + DM Sans (texto), portada editorial, aparición suave de secciones (respeta `prefers-reduced-motion`), indicador de sección activa y sección "Fuera del código". Para ejecutar localmente abre `index.html` en el navegador (no necesita instalación).

Pendiente de implementar: páginas de detalle por proyecto, materias del tercer cuatrimestre, y los proyectos 3 (tienda de productos naturales) y 4 (portafolio previo), que están por confirmar.
