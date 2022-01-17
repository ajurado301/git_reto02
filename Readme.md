# Crear y subir un proyecto a git
    1- Crear un nuevo repositorio local con git init
    2- Crear un nuevo repositorio en github
    3- Enlazar el nuevo repositorio local con el remoto
        git remote add origin <url_repositorio_remoto>
        git branch -M main
        git push -u origin main
    4- A partir de aquí usaremos los siguientes comandos:
        git add (para añadir las modificaciones al stage)
        git commit -m "descripción" (para incorporar el stage al repositorio main local)
        git push (para actualizar el repositorio remoto main con el repositorio local main)