# Dockerizacion-de-entorno

Documentación configuración de entorno

paso 1:

  verificar la version de python instalada mediante el comando
    - python -V o python --version
    para mas ayuda puede digitar el comando 
    - python --help

paso 2:

  Instalar docker para esto se digita lo siguiente
   - sudo apt install apt-transport-https ca-certificates curl software-properties-common-> instalar algunos paquetes previos necesarios
   - curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -  ->agregar el repositorio oficial al sistema
   - sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable" agregar el repositorio al APT
   - sudo apt update -> con el fin de actualizar la lista de paquetes existente
   - apt-cache policy docker-ce
   
paso 3: 
  Verificar si se tiene instalado el gestor de packetes de python por medio del siguiente comando
    -pip -version 
    si no se tiene instalado se instala por medio de el siguiente comando
    - sudo apt-get install python-pip
    
paso 4:
  Instalar la libreria de flask
    - pip install flask

    
