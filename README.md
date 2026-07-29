# Villas Glamping — Guía de experiencias

Sitio estático de una sola página (HTML/CSS/JS puro, sin frameworks ni build).
Todas las imágenes están embebidas dentro del propio `index.html`, así que
no hay carpeta de assets que gestionar por separado.

## Subir a GitHub (sin usar la terminal)

1. Entra a tu repo: https://github.com/asistentedigitalizados/villas-glamping
2. Click en **"Add file" → "Upload files"**
3. Arrastra los 3 archivos de esta carpeta:
   - `index.html`
   - `vercel.json`
   - `README.md`
4. Abajo, en "Commit changes", escribe un mensaje corto (ej: "Primera versión del sitio")
5. Click en **"Commit changes"**

## Conectar con Vercel (una sola vez)

1. Ve a **vercel.com** e inicia sesión con tu cuenta de GitHub
2. Click en **"Add New..." → "Project"**
3. Busca y selecciona el repo `villas-glamping`
4. Vercel detecta automáticamente que es un sitio estático — no cambies nada
5. Click en **"Deploy"**
6. En 30-60 segundos tendrás tu URL: algo como `villas-glamping.vercel.app`

## Cómo hacer cambios después (sin depender de Lovable ni de mí)

Cada vez que subas un archivo nuevo a GitHub (repitiendo el paso "Upload files"
de arriba y reemplazando `index.html`), Vercel **redeploya automáticamente**
en segundos. No hay que hacer nada más en Vercel.

Si más adelante quieres editar el código directamente en tu computadora sin
pasar por la web de GitHub, puedes usar **Claude Code** (se instala en tu
computadora) apuntando a la carpeta clonada del repo — te permite pedirle
cambios en lenguaje natural y él edita el `index.html` directamente.

## Dominio propio

Una vez desplegado, en Vercel puedes ir a **Project → Settings → Domains**
y conectar un dominio propio (ej. `villasglamping.com`) si lo compras después.
