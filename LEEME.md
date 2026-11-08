# Corneta Guía como app instalable (PWA)

Esta carpeta ya es una app completa. Solo hay que subirla a internet (con HTTPS, por el micrófono) y abrirla desde el teléfono.

## Qué contiene
- `index.html`: Corneta Guía (práctica nota por nota)
- `comandante.html`: Modo comandante
- `manifest.webmanifest`, `sw.js` e `icons/`: nombre, iconos y modo sin internet

## Publicarla gratis (elige una)

### Opción fácil: Netlify Drop
1. Entra a app.netlify.com/drop
2. Arrastra la carpeta completa. Te da una dirección web `https://...netlify.app`.

### Opción GitHub Pages
1. Crea un repositorio nuevo en GitHub (público).
2. Sube todos los archivos de esta carpeta (conserva la carpeta `icons`).
3. En Settings > Pages elige la rama `main` y la carpeta `/ (root)`.
4. En un par de minutos queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Instalarla en el teléfono
- **Android (Chrome):** abre la dirección y toca "Instalar" (o menú ⋮ > Instalar aplicación).
- **iPhone (Safari):** botón Compartir > "Agregar a pantalla de inicio".
- **Computadora (Chrome/Edge):** icono de instalar en la barra de direcciones.

La primera vez necesita internet. Después funciona sin conexión.

## Cuando cambies algo
Sube los archivos nuevos y cambia el número de `VERSION` en `sw.js` (por ejemplo `corneta-guia-v2`) para que los teléfonos descarguen la actualización.
