# Publicar y actualizar el portfolio de Laura en GitHub Pages

## Primera publicación (GitHub Desktop)

1. Descomprime el ZIP. Dentro está la carpeta Laura_Hernandez_Portfolio, con index.html, las hojas de estilo, los scripts y las carpetas img y fonts.
2. Crea tu cuenta en https://github.com si todavía no la tienes.
3. Instala GitHub Desktop desde https://desktop.github.com e inicia sesión con tu cuenta.
4. En GitHub Desktop selecciona File > New repository. Escribe portfolio en Name y elige dónde guardarlo. Pulsa Create repository.
5. Selecciona Repository > Show in Explorer (o Show in Finder en Mac). Se abrirá la carpeta del repositorio.
6. Copia DENTRO de esa carpeta TODO EL CONTENIDO de Laura_Hernandez_Portfolio: index.html, los demás archivos y las carpetas img y fonts. No copies la carpeta exterior ni subas el ZIP. index.html tiene que estar directamente en la raíz del repositorio. Incluye .nojekyll, si tu explorador lo muestra.
7. Regresa a GitHub Desktop. En Summary escribe Primera versión del portfolio y pulsa Commit to main. Si acabas de crear el repositorio y no ves cambios, comprueba que copiaste los archivos en la carpeta correcta.
8. Pulsa Publish repository. Deja el nombre portfolio, desmarca Keep this code private y confirma con Publish repository.
9. Abre el repositorio en github.com desde Repository > View on GitHub.
10. En GitHub entra en Settings > Pages. En Source elige Deploy from a branch. En Branch elige main y /(root). Pulsa Save.
11. Espera a que termine la publicación. Puede tardar hasta 10 minutos. En Settings > Pages aparecerá Visit site.
12. Si tu usuario es lauraejemplo y el repositorio se llama portfolio, tu enlace tendrá este formato: https://lauraejemplo.github.io/portfolio/. Sustituye lauraejemplo por TU usuario. Comparte el enlace que realmente aparezca en Pages.

## Actualizarlo después

1. Mantén la carpeta del repositorio en tu ordenador.
2. Antes de editar, abre GitHub Desktop y pulsa Fetch origin; si aparece Pull origin, púlsalo para incorporar los cambios publicados.
3. Si recibes otro ZIP actualizado, descomprímelo y copia el contenido de Laura_Hernandez_Portfolio dentro de la misma carpeta del repositorio, reemplazando los archivos cuando te lo pregunte. Conserva la carpeta .git y cualquier CNAME que hayas configurado para un dominio propio. No necesitas crear otro repositorio.
4. Para un cambio manual, abre la carpeta del repositorio en VS Code. Los textos de los proyectos están en project-content.js (en y es). El comportamiento está en main.js. El diseño se reparte en los archivos CSS. Las imágenes están en img. Para añadir un proyecto nuevo también hay que registrar sus rutas, portada y archivos; copiar una imagen sola no crea una ficha.
5. Guarda los cambios y abre index.html para revisarlos en tu navegador.
6. En GitHub Desktop escribe un resumen, por ejemplo Nuevas imágenes de Florario. Pulsa Commit to main y luego Push origin.
7. GitHub Pages publicará los cambios en el MISMO enlace. Espera unos minutos y recarga. Si ves una versión anterior, prueba Ctrl + F5 o una pestaña privada.

## Contacto y servicios externos

El portfolio es estático: no necesita una base de datos para mostrar sus trabajos. El formulario de contacto utiliza FormSubmit. Si no lo has hecho, envía un mensaje de prueba desde la web publicada y activa el formulario mediante el correo que reciba lauravhernandezmm@gmail.com. Después envía una segunda prueba y comprueba su recepción. Spotify y el envío del formulario necesitan conexión a Internet.

## Cambios de esta versión

- Móvil y tablet: desplazamiento vertical nativo con el dedo, sin barra lateral en las galerías.
- Inspiración y habilidades: también admiten un gesto horizontal para cambiar de imagen o habilidad.
- Modo claro/oscuro: botón junto al idioma en escritorio, y en la fila inferior del pie en móvil y tablet. La elección se conserva en el navegador cuando permite almacenamiento local.
- Playlist con un panel más alto.
- Las imágenes de inspiración llenan el marco con un borde uniforme. Para llenar todo el marco, pueden recortarse los bordes de algunas fotos.

Fuentes oficiales:
https://docs.github.com/en/desktop/overview/creating-your-first-repository-using-github-desktop
https://docs.github.com/en/desktop/adding-and-cloning-repositories/adding-an-existing-project-to-github-using-github-desktop
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
https://docs.github.com/en/desktop/making-changes-in-a-branch/committing-and-reviewing-changes-to-your-project-in-github-desktop
