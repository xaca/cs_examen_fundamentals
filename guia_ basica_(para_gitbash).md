# Si yo hice el repositorio, debo importarlo as�:

1. cd (arrastrar carpeta)
2. git clone (pegar link copiado de github) (es pa' descargar)
3. cd nombre_de_carpeta

# si voy a editar el proyecto que hizo otro:

1. hago fork en la p�gina de github.
2. cd (arrastrar carpeta)
3. git clone (pegar link copiado de github) (es pa' descargar)
4. cd nombre_de_carpeta (carpeta que tiene el mismo nombre del repositorio)
5. git checkout -b nombredemitree

------------------------------------------------------------------------------
## si necesito descargar actualizaciones que hicieron otros

git pull 

------------------------------------------------------------------------------

# Para subir mis actualizaciones

## si no he llegado a configurar el github:

1. git config --global user.email "micorreo"
2. git config --global user.name "minombre"
3. git add -A
4. git commit -m "se agrega una breve descripci�n de lo que se hizo :fire:"
5. git push
6. Ir al proyecto del due�o y solicitarle un pull.

## si ya lo configur� ignorar pasos 1. y 2.

------------------------------------------------------------------------------
# Otros comandos

* rm para borrar.
* ls (para ver que archivos hay)
-------------------------------------------------------------------------------
# si el computador en que trabaj� es de uso p�blico, en Windows debo:

1. ir a inicio.
2. buscar: administrador de credenciales.
3. click en "credenciales de windows".
4. quitar la credencial de github (git:https//github.com)

## de esta manera no podr�n editar mis proyectos otras personas.
