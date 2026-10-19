# El mejor escaparate — web propia

Web de una sola página (HTML + CSS, sin build) para publicar en Cloudflare Pages.

## Antes de publicar

Cambia estos datos con buscar y reemplazar en todos los archivos:

1. **WhatsApp:** `34600000000` → tu número con prefijo 34, sin espacios ni `+` (5 veces en `index.html`).
2. **Email:** `hola@elmejorescaparate.es` → tu email real (`index.html`, `aviso-legal.html`, `privacidad.html`).
3. **Dominio:** `elmejorescaparate.es` → tu dominio, si es otro (`index.html`, `robots.txt`, `sitemap.xml`, `aviso-legal.html`, `privacidad.html`, `404.html`).
4. **Datos del titular** en `aviso-legal.html` y `privacidad.html`: `[Nombre y apellidos]`, `[NIF]`, `[Dirección postal]`. Salen resaltados en la página hasta que los completes.

## Publicar

1. Sube la carpeta a un repositorio de GitHub.
2. Cloudflare Pages → conectar el repositorio. Sin comando de build; directorio de salida `/`.
3. Custom domains → añade tu dominio.
4. Google Search Console → añade el dominio y envía `sitemap.xml`.

## Opcional

- La tarjeta de la web de ejemplo es un dibujo hecho con CSS. Si prefieres una captura real, guárdala como `assets/img/ejemplo.webp` y sigue el comentario que hay en `index.html`.
- Cuando tengas las primeras reseñas reales de clientes, se añade una sección para ellas.
