# Guía de códigos para Git

### Crear configuración
`git config --global user.name 'nombre completo'`  
Agrega el nombre

`git config --global user.mail 'direccion@mail.com'`  
Agrega el correo electrónico

`git config --global core.editor 'code --wait'`  
Agregas VS Code como editor de Git

`git config --list`  
Para listar las propiedad que hemos configurado en Git  

### Crear un repositorio
`git init`
Crea un carpeta oculta con el metadata necesario para seguir el rastro en los cambios de los archivos.  

`git clone <url-repositorio>`  
Clona todos los archivos y los 'commits' de forma local  

### Seguir rastro de los cambios  
`git add <nombre-archivo>`  
Agrega el archivo especificado al 'stage area'  

`git add .`  
Agrega todos los archivos  

`git rm --cached <nombre-archivo>`  
Remueve el archivo del 'stage area' (No elimina el archivo)  



