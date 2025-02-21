# Comandos utilizados en clase de GIT

## Configuración inicial

#### Configurar el usuario y el correo:


Con estos comandos se realiza la configuración del usuario y del mail del usuario:

`git config --global user.name "Tu Nombre"`

`git config --global user.email "tuemail@example.com"`



#### Inicializando el repositorio:


Con estos comandos se realiza la parte dedicada a la iniciación de un repositorio:

`git init "repositorio""`

`git status`



Dependiendo de si queremos añadir un fichero en específico o queremos añadir todos los que esten
modificados, nuevos o eliminar los que ya no existen o estan marcados como que ya no existen:

En este caso se añadiran todos:

`git add .` 

En este otro se añadira solo el indicado en el comando:

`git add "fichero"`


