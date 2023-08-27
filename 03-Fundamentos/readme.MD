# APIREST

# Links

https://yirsis-serrano.notion.site/Node-js-y-GraphQL-e1bd0b2a0d2c4990a569a61fa0e4957f

https://yirsis-serrano.notion.site/Instalaciones-897d30b42c6a4d65a7597dd67b7ceab0

# Recursos

https://graphql.org/
	
https://www.apollographql.com/docs/apollo-server/

https://tableplus.com/windows

# Consumo de Api Rest - datasource-rest

## Install

npm install @Apollo/datasource-rest

ApiRest: https://jsonplaceholder.typicode.com/users

## Docker

docker build -t graphql-first-app:latest -t graphql-first-app:1.0.0 .

docker run -p 4000:4000 -d graphql-first-app

## Publicacion en Docker

graphql-first-app-jhba

comando push : docker push jhba/graphql-first-app-jhba:tagname

Configuraciones:

docker image tag graphql-first-app jhba/graphql-first-app-jhba


docker push jhba/graphql-first-app-jhba:tagname (en ejemplo se ejecuta sin tagname)

docker push jhba/graphql-first-app-jhba

## Publicando en Internet

1.- Publicar servicio en render.com o heroku
2.- Autenticarse en render o heroku con git
3.- Subir codigo a GIT con nombre de la APP


## Seccion 6 - DB en docker

docker pull mongo
docker pull mysql
docker pull postgres



