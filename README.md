# DIO-Spring-Parking
 - Realizando Deploy na Nuvem de um Conjunto de API’s Desenvolvida em Spring Boot.
 - Deployment feito no Azure App Service, Heroku comecou a ser apenas pago.

## Run database
docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123 -d postgres:10-alpine

## Start and Stop

### Stop Database
docker stop parking-db

### Start Database
docker start parking-db


