# GIT desarrollo colaborativo

Esto es una guia teorico practica para los alumnos de __"Git Desarrollo Colaborativo"__

## Configuracion Inicial

Cuando descargamos la herramienta __GIT__ debemos inicializar un proyecto en una carpeta a eleccion.
## Areas de Git
1. ___Working Directory___ El area de trabajo corresponde a la carpeta donde creamos el repositorio y vamosa crear, editar y trabajar los archivos q forman el proyecto
1. ___Staging Area___ El area de control de cambios, tambien llamada INDEX, se utiliza para realizar las capturas de codigo (SNAPSHOT), que luego deberan ser confirmadas si corresponden.
1. ___Repository___ El almacen de cambios correponde a una carpeta oculta que registra todas las confirmaciones en archivos BLOB, y que podemos consultar utilizando el historial de confirmaciones.
## Repositorio Remotos
Normalmente todos los cambios realizados se van a gestionar de manera local, pero una vez recopilado un conjunto de estos necesitamos publicarl dichas modificaciones en un repositorio de git.
Esto sirve para acceder desde cualquier otro lugar.
* __git clone 'url':__ clona un repositorio en el directorio actual
* __ git remote add 'alias' 'url':__ agrega una direccion de repositorio remoto al cual subir cambios.
* __ git remote rename 'old' 'new' :__ cambia el nombre de un repositorio remoto especificado

* __git remote set-url 'remote' 'url' :__ modifica la direccion url del remoto selecionado 

## Contacto
Para mas informacion consultar la Plataforma [alumni](https://alumni.education), donde tambien pueden realizar los examenes.