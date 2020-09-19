# Gestor de Clinetes
Gestor de Clientes con Python
Hay que instalar Python, Pip y Django, e instalar un Entorno Virtual. 
Ver tutoriales.

# Para Activar el Entorno Virtual:
pipenv shell

# Quick setup — if you’ve done this kind of thing before

https://github.com/mira-ceti/GestorClientes.git

# …or create a new repository on the command line

echo "# GestionClientes" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/mira-ceti/GestionClientes.git
git push -u origin master


# …or push an existing repository from the command line
           
git remote add origin https://github.com/mira-ceti/GestionClientes.git
git branch -M master
git push -u origin master

# Para cambiar a un repositorio remoto (hacerlo en un terminal nuevo de Ubuntu)
nano .git/config
## Y cambiar al repositorio con sus credenciales correspondientes:
[core]
        repositoryformatversion = 0
        filemode = true
        bare = false
        logallrefupdates = true
[remote "origin"]
        url = https://github.com/mira-ceti/GestorClientes.git
        fetch = +refs/heads/*:refs/remotes/origin/*
[branch "master"]
        remote = origin
        merge = refs/heads/master
[user]
        name = mira-ceti
        password = *********
        email = ibellon@gmail.com

# Volver a escribir el mensaje de confirmación más reciente
## Puedes cambiar el mensaje de confirmación más reciente usando el comando git commit --amend.

1. En la línea de comando, desplázate hasta el repositorio que contiene la confirmación que deseas modificar.

2. Escribe git commit --amend y presiona Enter (Intro).

3. En tu editor de texto, edita el mensaje de confirmación y guarda la confirmación.

## Puedes agregar un coautor al agregar una introducción a la confirmación. Para obtener más información, consulta "Crear una confirmación con múltiples autores".

## Puedes crear confirmaciones en nombre de tu organización agregando una introducción al mensaje de la confirmación. Para obtener más información, consulta "Crear una confirmación en nombre de una organización"

El nuevo mensaje y la confirmación aparecerán en GitHub la próxima vez que subas un cambio.

