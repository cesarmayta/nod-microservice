# nod-microservice
#despliegue de microservicios con node

#pasos
_1 instalar nvm (https://github.com/nvm-sh/nvm#installing-and-updating):

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

source ~/.bashrc

_2 instalar node

nvm install node
nvm install 14.16.1

_3 clonar el repositorio

git clone https://github.com/cesarmayta/nod-microservice.git

_4 instalar dependencias

npm install

_5 crear archivos .env
    PORT=5000
    DBUSER=
    DBHOST=
    DBPASSWORD=
    DBDATABASE=
    CATEGORIAS_PORT=5001
    MESAS_PORT=5002
    SECRET_KEY=qwerty123

