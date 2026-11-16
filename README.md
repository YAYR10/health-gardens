# Health Gardens · Nariño

Sitio web de Health Gardens: aventuras de turismo regenerativo, tienda de productos naturales (Botanic Health Gardens) y paseos en lancha por el Lago Guamuéz.

## Estructura
- `index.html` — la página completa (estilos, animaciones, tienda, lanchas, reservas y panel).
- `data.json` — el contenido publicado: textos, aventuras, productos, lanchas, aliados y acceso al panel.
- `img/` — fotos, logos y productos.

## Publicar en GitHub Pages
1. En GitHub: **Settings → Pages**.
2. En *Source* elige **Deploy from a branch**, rama **main**, carpeta **/ (root)** y guarda.
3. En uno o dos minutos la página queda en `https://<usuario>.github.io/health-gardens/`.

## Panel de administración
- Al final de la página toca **· Administrar** (o abre la dirección con `#admin` al final).
- Acceso inicial: `admin@healthgardens.co` / `Frailejon2026*`. **Cámbialo** en Panel admin → General → Acceso al panel.
- Lo que editas se guarda en tu navegador. Para publicarlo: Panel admin → General → **Descargar data.json**, reemplaza `data.json` en el repositorio (Add file → Upload files) y haz commit.

## Reservas, pedidos y pagos
- Reservas de aventuras y lanchas y pedidos de la tienda se envían al WhatsApp configurado en el panel.
- Cada visitante ve sus reservas y pedidos en su navegador.
- El pago en línea está en **modo prueba** (no cobra). Para cobrar de verdad hace falta una cuenta en una pasarela (por ejemplo Wompi) y un servidor que firme los pagos (por ejemplo Vercel).

## Probar en tu computador
Abre la carpeta en VS Code y usa la extensión **Live Server** sobre `index.html` (abrir el archivo con doble clic no carga `data.json`).
