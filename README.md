# Parrot Security OS - Community - General Questions
## Welcome Aboard Pirate

Quieres unirte al grupo de traducción Parrot Security OS en español?
Necesitas formar parte de algo grande? Crees que debes devolver a la comunidad todo aquello que esta hizo por ti?
Este es tu sitio....

## Quiero ayudar!!! Qué debo hacer? 


En primer lugar debes pasarte por el grupo de telegram https://t.me/joinchat/AAAAAECEF7201Jk3bOB5pA
Presentate y pasa unos dias con nosotros para saber si estás agusto y te apetece formar parte de esta gran familia. (Advertencia: no querrás dejarlo ;-) )
En dicho grupo, pregunta por el equipo de documentación y rápidamente te pondrán en contacto con alguno de los responsables de traducción y te darán las indicaciones adecuadas.


## Ya soy Contributor. Cómo funciona esto?

#### Clona el repositorio (sólo la primera vez)
<addr>git clone https://github.com/gesala/parrot_community_general
#### Descarga las modificaciones del repositorio
<addr>git pull
#### Selecciona alguno de los topics no traducidos y muévelo a trabajando/XXXX
XXXX -> tu nombre de usuario 
<addr>mv viewtopic.php\?id=1 trabajando/XXXX
#### Replica tu git local para que nadie elija el mismo documento
<addr>git push
#### Si crees que el documento no aporta valor al proyecto muévelo a basura
<addr>mv trabajando/XXXX/viewtopic.php\?id=1 basura
#### Si crees que tiene valor, modifícalo
<addr>vi trabajando/XXXX/viewtopic.php\?id=1
#### Una vez modificado, muévelo al sitio definitivo
<addr>mv trabajando/XXXX/viewtopic.php\?id=1 traducidas
#### Sube al repositorio las modificaciones
<addr>git push
#### Comienza de nuevo
Descarga de nuevo las modificaciones del repositorio
<addr>git pull
