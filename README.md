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

## Pendientes antes de entregar

1. **PixelShop**: el repositorio `github.com/Joseyta/PixelShop` está vacío. Sube el código (aunque sea una primera versión) para que el proyecto no cuente como vacío.
2. **Demos**: publica SRIU y PixelShop (Netlify, Vercel o GitHub Pages) y agrega un segundo enlace "Ver demo" en cada tarjeta de `index.html`.
3. **Nombre de SRIU**: el README del repositorio dice "SIIA+". Unifica el nombre en el repositorio y en el sitio.
4. **Idiomas**: en `script.js` edita `factOneText` (ES/EN/FR) y agrega tu nivel real de inglés y francés si quieres mostrarlo.
5. **Foto**: la actual mide 245×306 px. Con una foto de mayor resolución se verá más nítida; reemplaza `foto-245.webp` y `foto-490.webp`.
6. **LinkedIn**: abre el enlace desde el sitio publicado y confirma que lleva a tu perfil.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub, por ejemplo `portafolio`.
2. Sube `index.html`, `styles.css`, `script.js`, `assets/`, `README.md` y `CHECKLIST.md` a la rama principal.
3. En el repositorio abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**, elige la rama principal y la carpeta `/ (root)`, y guarda.
5. Espera la publicación y abre la URL que GitHub Pages muestra en esa sección.
6. Prueba el sitio publicado en móvil y escritorio; verifica también todos los enlaces.

## Publicar en Netlify

1. Inicia sesión en Netlify y selecciona la opción para añadir un sitio nuevo.
2. Puedes conectar el repositorio GitHub o arrastrar la carpeta del sitio descomprimida al área de despliegue manual.
3. No se necesita comando de build ni directorio de salida porque es un sitio estático.
4. Abre la URL asignada y revisa la navegación, traducciones y modo de color.

## Accesibilidad y funcionamiento

- Enlace para saltar al contenido, etiquetas semánticas, textos alternativos, controles etiquetados y foco visible.
- Menú móvil con estado `aria-expanded`.
- Respeta `prefers-reduced-motion`.
- Traducciones para español, inglés y francés.
- Modo claro/oscuro e idioma se recuerdan entre visitas (localStorage con manejo de errores).
- Los enlaces de GitHub, LinkedIn y correo usan los datos proporcionados; no se inventan demos ni certificaciones.

## Nota sobre contenido

SRIU se presenta como un prototipo académico con vistas para alumnos y administradores. PixelShop se describe como proyecto académico de tienda en línea. Las imágenes de las tarjetas son ilustraciones decorativas, no capturas de sistemas publicados.

## Rediseño "After Hours" (versión 4)

Paleta carbón/marfil/vino, Fraunces (títulos) + DM Sans (texto), portada editorial, aparición suave de secciones (respeta `prefers-reduced-motion`), indicador de sección activa y sección "Fuera del código". Para ejecutar localmente abre `index.html` en el navegador (no necesita instalación).

Pendiente de implementar: páginas de detalle por proyecto, materias del tercer cuatrimestre, y los proyectos 3 (tienda de productos naturales) y 4 (portafolio previo), que están por confirmar.
