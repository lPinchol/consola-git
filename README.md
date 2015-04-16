# Consola-git
==============
Probando la consola y comandos para git
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

touch README                    //Creas readme

git add README                  //Añades readme

git add .                       //Añade todos los archivos

git commit -m "tu primer comm"  //Añadir commit

git remote add origin           //Añadimos el remoto

git push origin master          //Mandas los commits  

git pull origin master          //Recibir la actualizacion   

git branch dev                  //Creacion de un branch

git checkout dev                //Cambiar a la rama Dev