(para pegar en la terminal shift + insert)


loguearse desde la terminal de git

* git config --global user.email "tuemail@ejemplo.com"

* git config --global user.name "tunombre"


generar token de autenticacion

https://docs.github.com/es/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token




crear un nuevo repositorio local

0) abrir la terminal de git en la carpeta del repositorio

1) git init 

2) git remote add origin "url del repositorio remoto"




subir cambios al repositorio remoto

1) git add .  

2) git commit -m "aca va el mensaje"

3) git push -u origin "nombre de la rama" (seteamos el upstream)

luego

4) git push origin "nombre de la rama" 



clonar un repositorio remoto

1) git clone "url del repositorio remoto"



actualizar el repositorio local 

1) git pull origin "nombre de la rama"  



crear una nueva branch 

1) git branch "nombre de la nueva rama"

OR

2) git checkout -b  "nombre de la nueva rama"




cambiar de branch

1) git checkout "nombre de la rama"



fusionar branches

1) git checkout "rama principal"

2) git fetch 

3) git merge "nombre de la rama a fusionar" 







