 Comandos básicos de Git

## Inicializar un repositorio

- `git init` => Crea un nuevo repositorio Git vacío en el directorio actual.

## Clonar un repositorio existente

- `git clone <url-del-repositorio>` => Crea una copia local de un repositorio remoto.

## Ver el estado del repositorio

- `git status` => Muestra el estado actual de los archivos en el repositorio (archivos modificados, no rastreados, etc.).

## Añadir archivos al área de preparación (staging area)

- `git add <archivo>` => Añade un archivo específico al área de preparación para el próximo commit.

- `git add .` => Para añadir todos los archivos.

## Realizar un commit

- `git commit -m "Mensaje del commit"` => Crea un commit con los cambios añadidos al área de preparación.  

## Ver el historial de commits

- `git log` =>  Muestra el historial de commits del repositorio.

## Crear una rama

`git branch <nombre-de-la-rama>` => Crea una nueva rama en el repositorio.

## Cambiar de rama

- `git checkout <nombre-de-la-rama>` => Cambia a una rama existente.

## Crear y cambiar a una nueva rama

- `git checkout -b <nombre-de-la-rama>` => Crea una nueva rama y cambia a ella.

## Fusionar ramas

- `git merge <nombre-de-la-rama>` => Fusiona los cambios de la rama especificada a la rama actual.

## Ver las ramas existentes

- `git branch` => Muestra una lista de todas las ramas en el repositorio.

## Subir cambios a un repositorio remoto

- `git push <remoto> <rama>` => Envía los cambios de la rama local a la rama remota.

## Descargar cambios de un repositorio remoto

- `git pull <remoto> <rama>` => Obtiene y fusiona los cambios desde el repositorio remoto.

## Eliminar una rama

- `git branch -d <nombre-de-la-rama>` => Elimina una rama local.

## Ver diferencias entre archivos

- `git diff` => Muestra las diferencias entre los archivos modificados y el último commit.
