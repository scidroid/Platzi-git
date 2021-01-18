# Git

## Comandos

### git init

inicia el repositorio

### git status

te muestra el estado de los archivos

### git add file.ext (. para toda la carpeta)

agrega un archivo al flujo de trabajo de git

### git rm archivo.ext (--cached para quitarlo completamente)

quitar un archivo del flujo de trabajo de git

### git config  (--list para configuracion por defecto)

te muestra todas as configuraciones que tiene git

### git config --global user.name "usuario"

agrega un nombre de usuario global

### git config --global user.email "usuario"

configura un email global

### git commit -m "mensaje" (-am para agregar los cambios y poner un mensaje)

mueve los archivos al repositorio

### git log (--stat para mas informacion)

te sirve para ver los cambios entre commits

### git show

muestra los cambios a detalle

### git diff commit1 commit2

compara el contenido de 2 commits

### git reset (--hard elimina el staging area) (--soft mantiene el staging area)

vuelve a un commit anterior

### git checkout commit archivo (si escribes el nombre de una rama y nada mas te cambia a ella)

devuelve archivos de un commit.

### git brach rama

crea una nueva rama

### git merge rama

fusiona 2 ramas en la actual

## GitHub y repositorio remoto

### git emote add nombre url

añade una dieccion de un repositorio remoto

### git remote (-v para mas información)

te muestra toda la información de los repositorios remotos.

### git pull repo rama

agrega a tu repositorio local los cambios de remoto

### git push repo rama

sube commits al repositorio remoto

### git tag -a nombre -m "mensaje" commit

agrega un tag a tu repositorio.

### git tag

te muestra los tags que tienes

### git show-ref --tags

te muestra e commit asignado al tag

### git push repositorio --tags

envia los tags a tu repositorio remoto

### git tag -d tag

elimina un tag

### git push repositorio:refs/tags/tag

elimina el tag borado localmente de un repositorio remoto

### git show-branch

Te muestra las ramas 

### git show-branch