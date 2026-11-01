# Pasos para iniciar el repositorio

1. Inicializar el repositorio en local

   `git init`

2. Indicar que archivos se prepararan para guardar

   2.1 Comando para guardar todos los archivos

   `git add .`

   2.2. Comando para guardar archivos especificos

   `git add nombreArchivo.extension`

   2.3. Comando para ver el estado de tu repositorio local

   `git status`

3. Comando para generar la versión con los archivos que se prepararon previamente

   `git commit -m "Nombre de la versión o descripción"`

4. Ir a tu cuenta de GitHub y crear tu nuevo repositorio.

5. Crear la rama principal "main" en nuestro repositorio.

   `git branch -M main`

6. Enlazar el repositorio en la nube con nuestro repositorio local.

   `git remote add origin https://github.com/Diego-Areco/mi-biblioteca-codigo.git`

7. Publicar los cambios del ultimo commit hacia nuestro repositorio en la nube.

   `git push -u origin main`
