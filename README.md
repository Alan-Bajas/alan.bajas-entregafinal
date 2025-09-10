# alan.bajas-entregafinal
Entrega 3 – Proyecto Web “Bar 80’s”
Descripción

Este es mi proyecto final del curso de Desarrollo Web. Hice un sitio para Bar 80’s con 5 páginas:

Inicio
Promociones
Carta
Eventos
Nosotros

La idea fue aplicar todo lo aprendido: HTML, CSS/SCSS, Bootstrap y diseño responsive.
Lo que hice según la rúbrica
HTML

Usé etiquetas semánticas como header, nav, main, section, footer.
Revisé que las imágenes tengan alt y que los enlaces funcionen entre todas las páginas.
Traté de mantener el código ordenado e indentado igual en todas las secciones.
CSS y SCSS
Pasé mis estilos a SCSS con la arquitectura 7–1 (carpetas de variables, mixins, base, layout, componentes y páginas).
Usé variables para colores (dorado y negro), tipografía y breakpoints.
Hice mixins para botones, media queries y tipografía fluida.
Apliqué nesting y usé @use en lugar de @import.

Estilos y diseño

Mantengo una paleta dorado/negro y tipografía Montserrat.
Agregué animaciones y transiciones
efecto fade-in en el hero de la página de inicio,
hover en las tarjetas y botones.

El sitio es responsive con Bootstrap (grillas y flexbox) más algunos mixins propios.

Responsive
Usé diseño mobile-first.
Tipografía y tamaños con clamp, rem y %.
Probado en celular, laptop y desktop.

Git y GitHub
Creé el repositorio, hice commits con los avances y subí todo (menos node_modules, que está en .gitignore).
Deploy con GitHub Pages para que se pueda ver online.

Cosas de optimización
Optimicé las imágenes.

El CSS final está en dist/css/main.css, que se genera con npm run sass.

Checklist final

 HTML limpio y semántico
 SCSS con 7–1 y mixins
 Animaciones y transiciones
 Responsive en distintos dispositivos
 Repo en GitHub con commits
 GitHub Pages funcionando
