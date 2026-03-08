
# Página romántica con video 💖

## Cómo usar
1. Coloca tu video MP4 en `video/mi-video.mp4` (respeta el nombre o actualiza `index.html`).
2. (Opcional) Reemplaza `img/poster.jpg` por una imagen de portada (mismo nombre).
3. Abre `index.html` para probar localmente (doble clic). 

## Publicar gratis

### Opción 1: GitHub Pages (recomendado)
1. Crea una cuenta en GitHub y un repositorio nuevo (público).
2. Sube todos los archivos del proyecto.
3. Ve a **Settings → Pages** y elige **Deploy from a branch**, selecciona `main` y carpeta `/root`.
4. Guarda; espera 1–2 minutos. Tu sitio quedará en `https://tuusuario.github.io/nombre-repo/`.

> Si el video pesa mucho, GitHub Pages lo sirve, pero puede tardar en cargar. Si falla, usa YouTube con iframe (ver comentario en `index.html`).

### Opción 2: Netlify Drop (súper fácil)
1. Ve a https://app.netlify.com/drop
2. Arrastra la carpeta del proyecto (o un `.zip`).
3. Te dará una URL del estilo `https://tusitio.netlify.app`.

### Opción 3: Vercel
1. Crea cuenta en https://vercel.com e importa el repositorio (o sube carpeta).
2. Deploy y usa la URL que te dé (por ejemplo `https://tusitio.vercel.app`).

### Opción 4: Neocities
1. Crea cuenta en https://neocities.org
2. Carga los archivos desde el panel.

## Generar un código QR del enlace
- Una vez que tengas la URL final, genera un QR con:
  - https://www.qr-code-generator.com/ o
  - https://www.qrcode-monkey.com/
- Descarga la imagen del QR y compártela por WhatsApp o imprímela.

## Notas
- Si usas YouTube: súbelo como **"No listado"** para que solo quienes tengan el enlace lo vean.
- Optimiza el MP4 para web (H.264 + AAC). Resolución 1080p es suficiente.
- Si cambias nombres de archivos, actualiza las rutas en `index.html`.
