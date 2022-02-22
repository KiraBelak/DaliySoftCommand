# DaliySoftCommand
Comandos de git

git clone <link del repositorio>
Es un comando para descargarte el código fuente existente desde un repositorio remoto

git add <archivo>
Añade un archivo al repositorio

git commit -m "mensaje de confirmación"
Una vez que se llega a cierto punto en el desarrollo, queremos guardar nuestros cambios 
Es como establecer un punto de control en el proceso de desarrollo al cual puedes volver más tarde si es necesario.
    
git push <nombre-remoto> <nombre-de-tu-rama>    
 Después de haber confirmado tus cambios, el siguiente paso que quieres dar es enviar tus cambios al servidor remoto. Git push envía tus commits al repositorio remoto.
 
git pull <nombre-remoto>
se utiliza para recibir actualizaciones del repositorio remoto. Este comando es una combinación del git fetch y del git merge lo cual significa que cundo usemos el git pull recogeremos actualizaciones del repositorio remoto (git fetch) e inmediatamente aplicamos estos últimos cambios en local (git merge).
    
git init
creará un nuevo repositorio local GIT    
