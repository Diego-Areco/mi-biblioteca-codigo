# Pasos para iniciar un repositorio

## Preparación

1. Crear una carpeta (por ejemplo: `mi-biblioteca-codigo`)
2. Abrir la terminal y navegar a la carpeta

## Comando básicos de Git

1. Inicializar el repositorio en local:

   `git init`

2. Indicar que archivos se prepararan para guardar:
   - Comando para guardar todos los archivos:

     `git add .`

   - Comando para guardar archivos especificos:

     `git add nombreArchivo.extension`

   - Comando para ver el estado de tu repositorio local:

     `git status`

3. Comando para generar la versión con los archivos que se prepararon previamente:

   `git commit -m "Nombre de la versión o descripción"`

4. Ir a tu cuenta de GitHub y crear tu nuevo repositorio.

5. Crear la rama principal "main" en nuestro repositorio:

   `git branch -M main`

6. Enlazar el repositorio en la nube con nuestro repositorio local:

   `git remote add origin https://github.com/TU-USUARIO/mi-biblioteca-codigo.git`

7. Publicar los cambios del ultimo commit hacia nuestro repositorio en la nube:

   `git push -u origin main`
