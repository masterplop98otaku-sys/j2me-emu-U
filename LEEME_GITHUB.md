# Compilar la VM J2ME para Wii U en GitHub
1. En github.com crea un repositorio nuevo (privado o publico) llamado, por ejemplo, `j2me-wiiu`.
2. Sube TODO el contenido de esta carpeta `github_build` a la raiz del repositorio (incluida la carpeta oculta `.github`).
   Si no puedes subir `.github`, en GitHub usa "Add file > Create new file", escribe el nombre
   `.github/workflows/build-cldc-wiiu.yml` y pega el contenido de ese archivo.
3. Ve a la pestaña **Actions**, elige "Compilar VM J2ME para Wii U" y pulsa **Run workflow**.
4. Espera unos minutos. Al terminar, descarga el artefacto `resultado-wiiu`.
   Si falla, abre el paso que fallo y copia aqui las ultimas ~80 lineas del registro (o adjunta `build.log` del artefacto).
