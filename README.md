# Consola-git
==============
> Probando la consola y comandos para git
==============

##Una vez instalado GIT, se hay que configurar:

git config --global user.name ""
git config --global user.email ""

##Generando la public key:

ssh-keygen

##Leyendo tu llave para copiarla a GitHub

cat ~/.shh/id_rsa.pub

##Arrancando tu proyecto:

git init                        //Iniciar git

git clone git:ruta github       //Clona un repositorio

touch README                    //Creas readme

echo "Texto" > Readme.md        //Crea un archivo con texto en su interior y se llamara readme.md

git add README                  //Añades readme

git status                      //Muestra el estado de git

git add .                       //Añade todos los archivos

git commit -m "tu primer comm"  //Añadir commit

git remote add origin           //Añadimos el remoto

git push origin master          //Mandas los commits  

git pull origin master          //Recibir la actualizacion 

git branch                      //Te muestra todas las ramas  

git pull origin master          //Recibir la actualizacion   

git branch dev                  //Creacion de un branch

git branch -d dev               //Eliminacion de la rama dev

git checkout dev                //Cambiar a la rama Dev

gitk                            //Saca la interfaz grafica

