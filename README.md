# consola-git
==============
Probando la consola y comandos para git

Una vez instalado GIT, se hay que configurar:

git config --global user.name ""
git config --global user.email ""

Generando la public key:

ssh-keygen

Leyendo tu llave para copiarla a GitHub

cat ~/.shh/id_rsa.pub

Arrancando tu proyecto:

git init                        //Iniciar git

touch README                    //Creas readme

git add README                  //Añades readme

git commit -m "tu primer comm"  //Añadir commit

git push origin master          //Mandas los commits     