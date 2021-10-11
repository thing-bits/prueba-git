# prueba-git
Mi primera práctica con git
<<<<<<< HEAD
=======

# Inicializar un repositorio local:

```
mkdir nombre-del-proyecto
cd nombre-del-proyecto
git init
```

# Crear y añadir ficheros (se puede crear tambien desde code):

```
touch nombre-del-fichero.extension otro-fichero.extension
git add nombre-del-fichero.extension otro-fichero.extension
```
Tambien se puede añadir todos los ficheros de una vez con el commando `git add .`.
Con esto se habrá pasado del working directory al staging.
Cada vez que se modifica los archivos hay que volver a añadirlos con `git add` antes de crear un commit.

# Crear un commit:

git commit -m " Descripción corta pero explicada de los cambios"

# Sincronizar un repositorio creado en github con el local:

```
git remote add origin repositorio
git branch -M main
git push -u origin main
```
El repositoro se puede ver en el botón code del repositorio que se desea clonar
En caso que sea una rama diferente hay que modificar main por la deseada

# crear una rama nueva y trabajar con ella:

```
git checkout dev
git branch dev
```
El primer commando crea la rama y el segundo cambia de directorio de trabajo por la rama elegida.
>>>>>>> dev
