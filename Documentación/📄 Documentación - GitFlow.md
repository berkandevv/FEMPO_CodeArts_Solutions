## Resumiendo el vídeo [https://www.youtube.com/watch?v=atYIzPIeeQk&t=3s](url)

# Git Flow

## Master
Es la rama por defecto al crear un repositorio. Es importante resaltar que **Master** es la rama que siempre debe contener la versión estable y lista para producción.

## Develop
Es donde se integra todo el trabajo de desarrollo de nuevas funcionalidades. Es recomendable que todos los desarrolladores trabajen sobre esta rama, y luego se haga un merge a **Master** cuando esté listo para producción.

## Feature
Se crea a partir de **Develop**, y es donde se trabaja en nuevas funcionalidades o mejoras. Al terminar, se hace un merge a **Develop**.

## Release
Esta rama se usa para preparar una nueva versión estable. Sin embargo, también se suelen hacer ajustes en esta rama (como correcciones menores, documentación, optimización de código) antes de hacer el merge en **Master**.

## Hotfix
Se utiliza para corregir errores críticos en producción de manera rápida. Se crea a partir de **Master** y, una vez solucionado el problema, se fusiona tanto en **Master** como en **Develop** (para que el cambio también se refleje en el desarrollo en curso).
