# Sandino Logística PWA (sin PNG/JPG)

Plantilla de repositorio lista para GitHub Pages: `index.html`, `manifest.webmanifest`, `icon.svg` (vector escrito en texto) y `sw.js`.

## Publicación
1. Descomprimir ZIP y cargar los cuatro archivos y este README en la raíz de un repositorio GitHub.
2. Repositorio > Configuración > Páginas > implementar desde una rama > `main` > `/ (root)` > Guardar.
3. Esperar la publicación.
4. En PWABuilder pegar URL de GitHub Pages y buscar empaquetado Android.

## App
Incluye registro básico de entregas, clientes, gastos, resumen de caja y exportación/restauración JSON. Datos almacenados localmente en navegador (localStorage), no sincronizados entre dispositivos. Hacer respaldos.

Se utiliza icono SVG sin archivos PNG/JPG. El empaquetador Android podría requerir iconos rasterizados adicionales; no se garantiza que PWABuilder acepte SVG para todos sus requisitos de empaquetado.

Esta plantilla no incorpora datos ni funciones del sistema original que no fueron compartidos como archivos fuente.
