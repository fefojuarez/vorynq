# VORYNQ — Sistema de Barra

Punto de venta para varias barras sincronizadas en tiempo real con Firebase.

- `index.html` — barra: cobro, tickets, stock, combos y tragos por ml, retiros, ventas y anulación, cierre con arqueo, usuarios con PIN, carga de carta por Excel.
- `vorynq-dashboard.html` — panel de organizadores (con usuario y contraseña): recaudación, ventas por hora, filtros, ranking, arqueos, historial, stock, exportar Excel, copia de seguridad.
- `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png` — permiten abrir el sistema sin internet e instalarlo como app.

Barra: https://fefojuarez.github.io/vorynq/
Panel: https://fefojuarez.github.io/vorynq/vorynq-dashboard.html

Datos en Firebase: proyecto propio `vorynq-79e90`, sección `vorynq`.
Reglas de Firebase: `firebase-reglas.json` (no se sube a GitHub, se pega en la consola de Firebase → Realtime Database → Reglas).
