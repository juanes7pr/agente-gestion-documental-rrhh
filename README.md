# Gestión Documental Inteligente de RR. HH. — Presentación interactiva

Presentación web de 20 diapositivas para la asignatura Tecnologías Disruptivas (plataforma Synergycomm). Autores: Juan Esteban Gutiérrez Parra y Andrés Felipe García Parra.

## Tecnologías
HTML5, CSS3 y JavaScript sin dependencias (Canvas para las partículas, Fullscreen API). Solo se carga la fuente Inter desde Google Fonts, con respaldo del sistema.

## Estructura
- `index.html`: página principal
- `src/slides.js`: contenido de las 20 diapositivas
- `src/main.js`: navegación, teclado, progreso y pantalla completa
- `src/background.js`: fondo de partículas
- `src/styles/style.css`: estilos

## Ejecutar localmente
Si algo no carga, usa `presentacion.html`: es la misma presentación en un solo archivo.
Abre `index.html` con doble clic, o ejecuta `npm start` (usa `npx serve`). No requiere instalar dependencias.

## Construcción
No hay paso de build: la carpeta ya es la versión de producción.

## Publicar en GitHub Pages
1. Sube el contenido de la carpeta a un repositorio.
2. En *Settings → Pages*, elige la rama `main` y la carpeta `/ (root)`.
3. La página quedará en `https://TU-USUARIO.github.io/NOMBRE-REPO/` (todas las rutas son relativas).

## Controles
→ / Espacio: siguiente · ←: anterior · Home: portada · End: última · botón ⛶: pantalla completa.
