docker build -t restauranteservice:1.1 .

docker run --name restaurante-service -p 8081:80 --network restaurante-bridge restauranteservice:1.1