# BarraUnder — Sistema de Barra UNDERHERTZ

Punto de venta para barras con sincronización en tiempo real vía Firebase Realtime Database
(proyecto `barra-underhertz`, compartido con la instalación original).

- `index.html` — sistema de barra (pedidos, cobro, stock, retiros, resumen, cierre).
- `underhertz-dashboard.html` — panel de control general.

## Publicar en GitHub Pages
1. Crear un repositorio nuevo (por ejemplo `BarraUnder`) y subir estos archivos a la rama `main`.
2. Settings → Pages → Source: *Deploy from a branch* → Branch `main`, carpeta `/ (root)` → Save.
3. En 1–2 minutos queda en `https://<usuario>.github.io/<repo>/`
   y el dashboard en `https://<usuario>.github.io/<repo>/underhertz-dashboard.html`.

## Notas
- PINs por defecto: operador `1234`, admin `0000`. Se cambian desde ⚙ → "Cambiar PINs".
- Comparte la base de datos con el sitio original: ventas, stock y productos son los mismos.
