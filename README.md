# Bar 80s – Entrega 3 (FINAL)

Este paquete contiene:
- 5 páginas HTML actualizadas (con clases `hero`, `promos`, `carta`, `eventos`, `nosotros` y `dist/css/main.css` linkeado).
- SCSS con arquitectura 7–1 en `src/scss/` (variables, mixins, base, layout, components, pages).
- `dist/css/main.css` ya listo para subir (se sobreescribe cuando compiles SASS).
- `.gitignore`, `package.json` (scripts de build) y este `README.md`.

## Cómo compilar SCSS
```bash
npm install
npm run sass
```
Compila `src/scss/main.scss` → `dist/css/main.css`.

## Subir a GitHub + GitHub Pages
1. Crea repo público y sube estos archivos (excepto `node_modules/`).
2. Commits claros (setup, html, scss, responsive, etc.).
3. Activa Pages: Settings → Pages → Deploy from branch (main, /root).
4. Verifica que el sitio cargue y aplique `dist/css/main.css`.

## Checklist
- HTML semántico; `alt` descriptivos; rutas relativas correctas.
- SCSS con variables, mixins, nesting y `@use` (arquitectura 7–1).
- Transiciones/animaciones y hover en elementos destacados.
- Responsive usando Grid/Flex (Bootstrap como base).
- Repo público + historial de commits + URL de Pages funcional.
