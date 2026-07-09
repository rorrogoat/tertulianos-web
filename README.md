# Tertulianos — sitio web

Sitio estático (HTML/CSS/JS puro, sin build). Variante "Casa Editorial".

## Publicar en Netlify

**Opción rápida — sin GitHub:**
1. Entra a https://app.netlify.com/drop
2. Arrastra esta carpeta completa a la página.
3. Listo, queda publicado con una URL de Netlify (se puede conectar un dominio propio después en Site settings → Domain management).

**Opción con GitHub (deploy continuo):**
1. Crea un repo vacío en https://github.com/new
2. Sube el contenido de esta carpeta al repo (arrastrando los archivos en la web de GitHub, o con `git push` si usas línea de comandos).
3. En Netlify → Add new site → Import an existing project → conecta ese repo.
4. Build command: (dejar vacío) — Publish directory: `.`

## Estructura
- `index.html` — la página completa
- `scout/` — fotografía
- `assets/` — logos e íconos
