# Seguridad & Talento

Landing page estática para servicios de asesoría en SST y gestión humana en Santiago de Cali, Colombia. No necesita instalación de dependencias ni proceso de compilación.

## Estructura para GitHub Pages

La página y sus imágenes deben quedar juntas en la raíz de la rama publicada:

```text
/
├── index.html
├── logo.png
├── hero.jpeg
├── trabajo.jpg
├── asesoria.jpg
├── verificacion.jpg
├── gestion.jpg
└── .nojekyll
```

Las rutas de las imágenes son relativas a `index.html`. No las muevas a una subcarpeta `assets/` a menos que también actualices las rutas de la página.

## Publicar o actualizar en GitHub Pages

1. Abre el repositorio `dmmarin97/Dmmarin` en GitHub.
2. Sube o reemplaza `index.html` en la raíz, conservando las imágenes existentes junto a él.
3. Si subes desde una copia local nueva, incluye también `logo.png`, `hero.jpeg`, `trabajo.jpg`, `asesoria.jpg`, `verificacion.jpg` y `.nojekyll` en la raíz.
4. En **Settings → Pages**, configura **Deploy from a branch**, selecciona la rama `main` y la carpeta **/(root)**.
5. Espera a que finalice el despliegue y recarga el sitio publicado. Si el navegador conserva la versión anterior, prueba una recarga forzada con `Ctrl+F5`.

Para actualizar desde Git, agrega los archivos en la raíz del repositorio y publica los cambios en `main`:

```powershell
git add index.html README.md .nojekyll logo.png hero.jpeg trabajo.jpg asesoria.jpg verificacion.jpg gestion.jpg
git commit -m "Fix GitHub Pages image paths"
git push origin main
```

## Formulario

El formulario valida los campos y muestra una confirmación en el navegador, pero no envía ni almacena mensajes. Para recibir consultas, conéctalo a un servicio de formularios o a un backend.
