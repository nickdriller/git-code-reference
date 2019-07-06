# Guía de códigos para Git

## Crear configuración
### Al instalar Git por primera vez se debe realizar una configuración que permite identificar cada *Commit* al usuario. Estos datos son el nombre y el correo electrónico. También se puede configuar el editor que queremos usar para realizar algunas funciones con Git 
---  

`git config --global user.name 'nombre completo'`  
Agrega el nombre

`git config --global user.mail 'direccion@mail.com'`  
Agrega el correo electrónico

`git config --global core.editor 'code --wait'`  
Agregas VS Code como editor de Git

`git config --list`  
Para listar las propiedad que hemos configurado en Git