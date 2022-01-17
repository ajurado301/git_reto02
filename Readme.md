# Crear y subir un proyecto a git
    1- Crear un nuevo repositorio local con git init
    2- Crear un nuevo repositorio en github
    3- Enlazar el nuevo repositorio local con el remoto
        git add . (para añadir el proyecto al stage)
        git commit -m "descripción" (para incorporar el stage al repositorio main local)
        git branch -M main
        git remote add origin <url_repositorio_remoto>
        git push -u origin main
    4- A partir de aquí usaremos los siguientes comandos:
        git add (para añadir las modificaciones al stage)
        git commit -m "descripción" (para incorporar el stage al repositorio main local)
        git push (para actualizar el repositorio remoto main con el repositorio local main)

#   .gitignore
    Cuando subimos los cambios al repositiorio omite los archivos especificados en .gitignore en este caso los archivos con extensión png de las carpetas especificadas:

    reto_2\*.png
    reto_3\*.png
    reto_4\*.png
    
    Nota: El proyecto de git a partir del reto 2 le he llamado git_reto02 así que el resto de retos se han hecho sobre este. Añado también el resto de carpetas de capturas que he ido creando en este proyecto