docker build -t hashes . 

docker run -p 8080:8081 -it hashes

docker-compose build && docker-compose up --scale node=2

docker-compose --scale node=10
