# Django_practica
# Nuevo intento de realizar un proyecto con Django. Anteriormente he tenido problemas relacionados con la configuración: pipenv, VSC, etc. y quiero volver a este framework para 
ver si logro entenderlo.
# Primer paso: crear la carpeta donde incluiré el proyecto. 
# Segundo paso: colocarte en esta carpeta con el símbolo del sistema (cmd) de Windows y escribir git init.
# Tercer paso: abrir la carpeta en VSC.
# Cuarto paso: abrir una nueva terminal en este directorio.
# Quinto paso: instalar pipenv "pip install pipenv". El sistema me indica que ya tengo instalado pipenv con "_Requirement already satisfied_".  
Con pipenv instalado, no se necesita usar "pip" y "virtualenv" por separado.
El comando "pipenv -h" proporciona ayuda sobre pipenv.
Ya que el uso de "requirements.txt" puede llegar a ser problemático, pipenv utiliza "pipfile" y "pipfile.lock" para registrar los paquetes instalados y las dependencias de cada paquete.
# Sexto paso: con pipenv instalado, en el mismo directorio y con el comando "pipenv shell", me permite activar y administrar un entorno virtual pipenv.
# Séptimo paso: con el comando "pipenv install django", instalo el Django en el entorno virtual que tengo activado.
# Octavo paso: creo un fichero ".gitignore" en la carpeta raíz de este proyecto. En la página "https://gitignore.io" creamos el código para añadir a este fichero. Solo hace falta usar las etiquetas "visualstudiocode; python; django" y darle a "create". El código que se crea lo copio y lo pego en el fichero ".gitignore".
# Noveno paso: siguiendo en VSCode, compruebo que en la carpeta de mi directorio que no aparece nada sobre Django. He reiniciado y he elegido el intérprete de Python (menú Ver/Paleta de comandos); al abrir una nueva terminal, me ha dado un error y he decidido borrar este proyecto. Creo que el error provenía porque he comenzado el proyecto en cmd en modo administrador.
# Décimo paso: creo una nueva carpeta.
# Undécimo paso: abro este directorio en cmd, en modo no administrador.
# Duodécimo paso: en este directorio, escribo "git init", cuyo resultado es "Initialized empty Git repository in C:/Users/soyed/OneDrive/Escritorio/Django/.git/".
# Decimotercer paso: siguiendo en cmd, con el comando "code ." en este mismo directorio, lo abro en VSCode.
# Decimocuarto paso: repito el octavo paso. Desde el noveno paso hasta este, he seguido lo indicado en "https://dev.to/iamjonathanpumares/configura-tu-entorno-de-desarrollo-de-manera-profesional-con-python-y-django-335g", pero, ya que yo quiero hacer este proyecto con Django y pipenv y en esta página sigue con env, seguiré desde el quinto paso hasta el séptimo paso.
# Decimoquinto paso: en VSCode, elijo el intérprete de Python y le doy la ruta que me indica cuando he creado el entorno virtual con "pipenv shell", "C:\Users\soyed\.virtualenvs\Django-n9IHszNr".
# Decimosexto paso: instalo Django en el entorno virtual con cmd. En cmd sí me aparece algo que me indica como que el entorno virtual está activado y estoy en él: entre paréntesis, a la izquierda del directorio "C:\Users\soyed\OneDrive\Escritorio\Django>", aparece "(Django-n9IHszNr)". En VSCode, en cambio, por ahora no aparece nada parecido.
# Decimoséptimo paso: sigo en cmd y escribo en este directorio "django-admin startproject miproyecto .". El punto final tras "...miproyecto..." indica que este proyecto se va a crear en el mismo directorio y no en otro. Si no hubiese escrito ese punto, se habría creado otra carpeta/directorio dentro de "C:\Users\soyed\OneDrive\Escritorio\Django>".
# Decimoctavo paso: en cmd, escribo "py manage.py runserver". Esto abre un servidor local de desarrollo en "http://127.0.0.1:8000". Antes de ir a esta url, debo realizar unas migraciones, que es como Django almacena los cambios en sus modelos.
# Decimonoveno paso: con "ctrl + c" (CTRL-BREAK), cierro el servidor.
# Vigésimo paso: en cmd, escribo "py manage.py migrate" y me realiza las migraciones. Abro otra vez el servidor para comprobar que todo va bien.
# Vigesimoprimer paso: 
