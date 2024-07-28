docker build -t itemservice:1.1 .

docker run --name item-service -d -p 8080:80 --network restaurante-bridge itemservice:1.1