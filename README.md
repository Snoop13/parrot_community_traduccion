# EN CONSTRUCCION

# Parrot Security OS - Community - General Questions - ESPAÑOL
## Al abordaje, pirata!!!!

Quieres unirte al grupo de traducción Parrot Security OS en español?
Necesitas formar parte de algo grande? Crees que debes devolver a la comunidad todo aquello que esta hizo por ti?
Este es tu sitio....

## Quiero ayudar!!! Qué debo hacer? 


En primer lugar, debes pasarte por el grupo de telegram https://t.me/joinchat/AAAAAECEF7201Jk3bOB5pA .
Preséntate y pasa unos días con nosotros para saber si estás a gusto y te apetece formar parte de esta gran familia. (Advertencia: no querrás dejarlo ;-D ).
En dicho grupo, pregunta por el equipo de documentación y rápidamente te pondrán en contacto con alguno de los responsables de traducción y te darán las indicaciones adecuadas.


## Ya soy Contributor. Cómo funciona esto?

#### Clona el repositorio (sólo la primera vez)
`git clone https://github.com/gesala/parrot_community_traduccion`
#### Descarga las modificaciones del repositorio
`git pull`
#### Accede al directorio raiz del proyecto
`cd parrot_communitty_traduccion`
#### Accede a los diferentes directorios que se cooresponden con los "boards" de la página web
* Advanced_topics
* development
* general
* hacking
* installation
* programming
* spanish_community
* system_setup
#### Selecciona alguno de los topics no traducidos y muévelo a trabajando/XXXX
XXXX -> tu nombre de usuario.  
`mv viewtopic.php\?id=1 ../trabajando/XXXX`
#### Replica tu git local para que nadie elija el mismo documento
`git push`
#### Si crees que el documento no aporta valor al proyecto muévelo a basura
`mv trabajando/XXXX/viewtopic.php\?id=1 ../basura`
#### Si crees que tiene valor, modifícalo
`vi trabajando/XXXX/viewtopic.php\?id=1`
#### Una vez modificado, muévelo al sitio definitivo
`mv trabajando/XXXX/viewtopic.php\?id=1 traducidas`
#### Sube al repositorio las modificaciones
`git add .`  
`git commit`  
`git push`
#### Comienza de nuevo
Descarga de nuevo las modificaciones del repositorio.  
`git pull`

# Asciinema
Hay un pequeño asciinema (parrot_contributor.json) en el que puedes ver el proceso.

Tras instalar asciinema:  

`asciinema play parrot_contributor.json`
