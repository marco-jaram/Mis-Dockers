# Info
## Crear carpeta data
mkdir data

## Entrando a mi contendero mongo
❯ docker exec -it monguito bash

## Creando simbolo para comando mongosh y que sea mongo
root@153953885c25:/# ln -s /usr/bin/mongosh /usr/bin/mongo

## Ingresando a mongo
mongosh -u tu_usuario -p tu_contraseña --authenticationDatabase=admin

mongo -u root -p secret \303\261a --authenticationDatabase=admin


