# GIT

## Comandos:

### Comandos globales:

+ git --version
    >Me muestra mi version actual de git.
+ git config --global user.name "usuario de github"
    >Asigna mi usuario a mi compu.
+ git config --global user.email "asignar el correo que corresponde al usuario de github"
+ git config user.name 
    >Nos enseña el usuario actual.
+ git config user.email
    >Nos enseña el correo del usuario actual.
+ Is
    >Nos muestra la lista de archivos en la carpeta que estemos.

#### Comandos de repositorios:

+ git init
    >Inicia el repositorio (agrega la palabra master en celeste a la ruta)
+ git status
    >Nos muestra el estado de todos nuestros archivos.
    + rojo: Untracked
    + verde: Stage
+ git add
    >(incluir nombre si solo quiero 1)
+ git add .
    >agrega a Stage todos los archivos
+ git commit -m "descripción"
    >Agrega al repositorio todo lo que está en Stage con un nombre y marca de tiempo.
+ git log
    >Nos muestra el historial e información de los commit

### Comandos de repositorio remoto (github):
+ git remote add origin https://github.com/Majo2005/hola-mundo.git 
     >Agrega con el nombre origin la ruta remota
+ git push -u origin master
    >Empuja la rama master a la ruta remota
+ git pull origin
    >Jala el repositorio desde la ruta remota.
    + Al existir conflictos:
        >Primero: seleccionar el cambio a mantener
        >Segundo: Realizar un git add
        >Tercero: Realizar un commit
        >Esto solucionará el conflicto y me permitirá seguir trabajando

